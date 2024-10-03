# What is for this repository?

Provide project's explanation
Provide project's structure documentation
Provide project's questlogs, coming features and features

	Project name: rsproj - 

	[ Another project of..
		minimalist Operation System (Linux Distro) 
			user and developer friendly
				with integration of...
				nowdays technologies:
					Node.js + qt + Wayland + HTML }

## Repositrios first-level

1. core - (fsys prefefinitions, system setup scripts, patchers)
2. docs - this repository (entry point)
3. wsps - devel vscode workspace files

## Repositorios namespaceds

apps_*

deps_*
	
	deps_qtc6
	deps_gtk-nocsd

api.js_*

	rsp.js_tools (programatic .js API node.js based for developers on @rsp OSys)
	rsp.js_ssp (pm2 remaster - @rsp serviceManager CLI and programatic .js API)
		rsp.js_ssp-io
		rsp.js_ssp-agent
		rsp.js_ssp-js-api
	






#  ~ All this directory is going into Cubic terminal page

## ./script.dev - Scripts used for development automation
	
	 ~ they control extends over all the other directories
	 ~ used scritly thoughtout package.json script's
	 
## ./script.setup - Scripts used to setup the system 
	
	 ~ used by ./script/dev
	 ~ wheather on host environment; for development.
	 ~ wheather on the Cubic environment; for test & release.

## ./project - Native systems's software project's source codes.
	
	 ~ used by ./script/dev > ./script.setup
	 ~ subprojects to implemented on the project
	 ~ wheather on host environment; for development.
	 ~ wheather on the Cubic environment; for test & release.

## ./asset - Files, media used to compose the project 
	
	 ~ used by ./script/dev > ./script.setup
	 ~ content is dump on ./fsys 
	 ~ wheather for development 
	 ~ wheather for test & release

## ./fsys - The main directory of de project

	 ~ used passively by the other part's
	 ~ for implementation/merge operations
	 ~ think of it as a /src directory on implementation/merge
	 ~ think of it as a /dist directory where development workflow dump on.



1. run "script/setup/05.fix"
2. run "script/setup/10.apt"
3. run "script/setup/15.node"
3. run "script/setup/20.denv"

5. Reboot
6. run "startx"

7. run "script/setup/33.greet"
8. Reboot for test.

9. run 

