# install sorce

you will need to install zlib-devel and libssl-dev. by executing these two command:
`sudo dnf install dh-autoreconf curl-devel expat-devel gettext-devel \
  openssl-devel perl-devel zlib-devel`

``
dnf is only used for fedora linix destro
in this case its debian so to install git use this command:
`sudo apt-get install dh-autoreconf libcurl4-gnutls-dev libexpat1-dev \ gettext libz-dev libssl-dev`
to view the document yow will need xml to docbook2X in asciidoc by useing thiscomand
`sudo dnf install asciidoc xmlto docbook2X`

dnf is only used for fedora linix destro
in this case its debian so to install git use this command:

`sudo apt-get install asciidoc xmlto docbook2x`

note: Users of RHEL and RHEL-derivatives like CentOS and Scientific Linux will have to enable the EPEL repository to download the docbook2X package.

but lets get back on goin to install git.
you will need install info, by useing this command:
`sudo apt-get install install-info`

Additionally, if you’re using Fedora/RHEL/RHEL-derivatives, you need to do this:

`sudo ln -s /usr/bin/db2x_docbook2texi /usr/bin/docbook2x-texisudo ln -s /usr/bin/db2x_docbook2texi /usr/bin/docbook2x-texi`
now dowload git, useing wget by going the command:
`wget -o git.tar.gz https://mirrors.edge.kernel.org/pub/software/scm/git/git-0.01.tar.gz`