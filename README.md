This is the config to run a cosmo router locally which federates the subgraphs in the following projects:

- https://github.com/spavett/posts-and-authors-graph
- https://github.com/spavett/image-graph
- https://github.com/spavett/tag-graph

- Clone those repos and npm install then npm run start:dev. 
- Install the Wundergraph CLI wgc npm install -g wgc@latest (https://cosmo-docs.wundergraph.com/cli/intro)
- Download and extract the latest cosmo router build for your system to this folder (https://github.com/wundergraph/cosmo/releases?q=router&expanded=true)
- run wgc router compose -i compose.yaml -o config.json in this folder to generate the fed graph config (https://cosmo-docs.wundergraph.com/tutorial/mastering-local-development-for-graphql-federation)
- start your router (./router)
