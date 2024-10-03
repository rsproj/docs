# @rsp - Services Manager/Units

### pattern:

    rsp.sys.serviceManager <serviceName>.ssp

# @rsp - CLI Native Applications suite

### pattern:

    rsp.<namespace>.<appName>
        rsp.<appName> (symlink)
            <appName> (symlink)

# @rsp - Desktop Native Applications suite

### pattern:

    rsp-<app-name>

# @rsp - Desktop Environment Core Software Kit

### pattern:

    <appname>sp
        rsp-<appname>sp (symlink)

## Compositor de janelas

    wmsp
    rsp-wmsp
    /wmsp.cc (project directory)

## Barra fixa de topo

    barsp
    rsp-barsp
    /barsp.cc (project directory)

## Painel de dock

    pnsp
    rsp-pnsp
    /pnsp.cc (project directory)

## Servico de background settlement

    bgmsp
    rsp-bgmsp
    /bgmsp.cc (project directory)

## Servico de desktop surface directory

    dsfsp
    rsp-dsfsp
    /dsfsp.js (project directory)