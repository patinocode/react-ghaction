# react-ghaction
React application with build with GH Actions and publishes to GH Pages.

# directory structure [WIP]
```
.
└── README.md
    └── .github
        └── workflows
            └── react-build.yaml
└── package.json
```

# Build Image
`docker build -t react-ghaction:local .`

# Run Image [ Local ]
`cd ~/WorkSpace/react-ghaction # CHANGE THIS TO YOUR SOURCE DIR`

`docker run --rm --name react-ghaction -it --entrypoint bash -v ${PWD}:/opt/react-ghaction react-ghaction:local`