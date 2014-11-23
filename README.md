# Symfony training

In order to start using this training:

* `git clone --recursive --branch symfony_training git@github.com:OXID-eSales/olis.git ; cd olis`
* Create a new repository under your account as `symfony-training`
* `git remote add upstream git@github.com:<username>/symfony-training.git`
* `git push upstream symfony_training:master`
* `cd .. ; rm -rf olis`
* `git clone --recursive git@github.com:<username>/symfony-training.git`
* `vagrant up` and at this point it's a good idea to grab coffee/tea/beer

# Virtual machine differences

* **Global configuration** (from `developer_environment` branch as *submodule*): `./puphpet/config.yaml`
* **Project configuration** (included in this repository): `./.puphpet/config.yaml`
* **Local configuration** (ignored by git, local changes only): `./.puphpet/.config.yaml`
