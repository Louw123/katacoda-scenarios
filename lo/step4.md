then compile git by useing this command:

``tar -zxf git-2.8.0.tar.gz |
cd git-2.8.0 |
make configure |
./configure --prefix=/usr |
make all doc info |
sudo make install install-doc install-html install-info``{{execute}
congrats, you installed git! however you need to update to the latest version by useing this finnal command: 
`git clone git://git.kernel.org/pub/scm/git/git.git`{execute}