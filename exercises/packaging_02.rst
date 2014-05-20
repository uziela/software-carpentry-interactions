Exercise 02:

Create the setup.py file, replacing the information with the proper one::


  from distutils.core import setup

  setup(
      name="scbctesting",
      version="0.1.0",
      description="Sample project",
      author="Firstname Lastname",
      author_email="contact@example.com",
      license='BSD',
      url='http://github.com/ogrisel/scbctesting',
      packages=['scbctesting'],
  )
