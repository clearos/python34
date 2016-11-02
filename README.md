git clone git+ssh://git@github.com/clearos/python34.git
cd python34/
git checkout epel7
git remote add upstream git://pkgs.fedoraproject.org/python34.git
git pull upstream epel7
git checkout clear7
git merge --no-commit epel7

