# django_website
training_django_project


### memo : 
min protocol = SMB2

semanage fcontext -a -t samba_share_t '/home/django/project(/.*)?'

restorecon -R -v project/

yum install python36

python36 -m ensurepip --default-pip

python36 -m pip install django
