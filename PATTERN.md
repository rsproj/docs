################################################
# @rsp - Services Manager/Units ################
################################################

## pattern:

    rsp.service <serviceName>
        ssp.<serviceName> (symlink)

################################################
# @rsp - CLI Native Applications suite #########
################################################

## pattern:

    rsp.<namespace>.<appName>
        rsp.<appName> (symlink)
            <appName> (symlink) 

################################################
# @rsp - Desktop Native Applications suite #####
################################################

## pattern:

    rsp-<app-name>

################################################
# @rsp - Desktop Environment Core Software Kit #
################################################

## pattern:
    
    <appname>sp

- Compositor de janelas

wmsp (binary)
rsp-wmsp (symlink)
wmsp.cc (project directory)

- Barra fixa de topo

barsp
rsp-barsp (symlink)
barsp.cc (project directory)

- Painel de dock

pnsp
rsp-pnsp(symlink)
pnsp.cc (project directory)

- Servico de background settlement

bgmsp
rsp-bgmsp (symlink)
bgmsp.cc (project directory)

- Servico de desktop surface directory

dsfsp
rsp-dsfsp (symlink)
dsfsp.js (project directory)

