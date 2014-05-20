Create a file: MANIFEST.in next to setup.py with the content::

  include README.md
  include LICENSE.txt
  recursive-include interactive *

Then run::

  $ python setup.py sdist
