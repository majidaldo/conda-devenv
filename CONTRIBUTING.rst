============
Contributing
============

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

You can contribute in many ways:

Types of Contributions
----------------------

Report Bugs
~~~~~~~~~~~

Report bugs at https://github.com/ESSS/conda-devenv/issues.

If you are reporting a bug, please include:

* Your operating system name and version.
* Any details about your local setup that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.

Fix Bugs
~~~~~~~~

Look through the GitHub issues for bugs. Anything tagged with "bug"
and "help wanted" is open to whoever wants to implement it.

Implement Features
~~~~~~~~~~~~~~~~~~

Look through the GitHub issues for features. Anything tagged with "enhancement"
and "help wanted" is open to whoever wants to implement it.

Write Documentation
~~~~~~~~~~~~~~~~~~~

conda-devenv could always use more documentation, whether as part of the
official conda-devenv docs, in docstrings, or even on the web in blog posts,
articles, and such.

Submit Feedback
~~~~~~~~~~~~~~~

The best way to send feedback is to file an issue at https://github.com/ESSS/conda-devenv/issues.

If you are proposing a feature:

* Explain in detail how it would work.
* Keep the scope as narrow as possible, to make it easier to implement.
* Remember that this is a volunteer-driven project, and that contributions
  are welcome :)

Get Started!
------------

Ready to contribute? Here's how to set up ``conda-devenv`` for local development.

1. Fork the ``conda-devenv`` repo on GitHub.
2. Clone your fork locally::

    $ git clone git@github.com:your_name_here/conda-devenv.git

3. Create a new conda environment for developing::

    $ conda create -c conda-forge -n devenv --file requirements_dev.txt
    $ source activate devenv
    $ pre-commit install
    $ pip install -e .

4. Run tests to ensure you are starting from a working state::

    $ pytest tests

5. Create a branch for local development::

    $ git checkout -b name-of-your-bugfix-or-feature


6. Now make your changes and commit.

7. When you're done making changes, check that your changes still pass the tests::

    $ pytest tests

8. Commit your changes and push your branch to GitHub::

    $ git add .
    $ git commit -m "Your detailed description of your changes."
    $ git push origin name-of-your-bugfix-or-feature

9. Submit a pull request through GitHub.

Pull Request Guidelines
-----------------------

Before you submit a pull request, check that it meets these guidelines:

1. The pull request should include tests.
2. If the pull request adds functionality, the docs should be updated. Put
   your new functionality into a function with a docstring, and add the
   feature to the list in README.rst.
3. The pull request should work for Python 3.6, 3.7 and 3.8. Check
   https://github.com/ESSS/conda-devenv/actions?query=event%3Apull_request
   and make sure that the tests pass for all supported Python versions.
