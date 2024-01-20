## Django blog website with AWS file upload 
_____________________________________________________
This is an old project of mine and uses Django 2.1
_____________________________________________________

To use the source code:

1. Clone the repository
```python
git clone https://github.com/ShrishtiKarkera/django-blog.git
```

2. Install django in your IDE
```python
pip install django == 2.1
```
3. Run the django server:
```python
python manage.py runserver
```
You can now run the django blog website locally and you can deploy it on the platform of your choice. I chose AWS.

To deploy it on AWS:

1. Create an account - https://aws.amazon.com/console/
2. Create an S3 bucket to store the files
3. Then create an user in AWS resource groups and grant the user permissions to access the S3 bucket using existing policies (AmazonS3FullAccess)
4. Create an instance and clone the repo there
You are now able to run this blog application on AWS. 
