Contributing to IncludeOS
=========================

Fork, edit and send us a pull-request on GitHub
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

IncludeOS is being developed on GitHub. Create your own fork, send us a pull request and `chat with us on Gitter <https://gitter.im/hioa-cs/IncludeOS>`__.

You're very welcome to `clone, edit and send pull-requests <https://help.github.com/articles/using-pull-requests>`__.

Send any and all pull-requests to the `dev-branch <https://github.com/hioa-cs/IncludeOS/tree/dev>`__. It's ok if it comes from your master branch.

1. Do "one thing" pr. pull-request. This makes it possible to quickly see and understand what you've done.

2. Everything you commit will be under the same license as this repository and the copyright holders of said repository will retain the right to publish your commits under a different license.

3. State what you have done in the commit message. Avoid general terms like "minor changes". Commit messages should also be short so pt. 1 is important.

4. Commit messages should indicate which major component the commit makes changes to. Good commit messages have a subject line that starts with the name of the major component that is modified by the commit:

   -  virtionet: Increased buffers for packets
   -  test: Update bufferstore test
   -  crt: Manually realign heap to at least 16 byte boundary

5. Avoid lots of reformatting and program changes in the same commit. If you're making drastic changes to a file, but mostly adding comments, reformatting, cleaning up etc., please do this in a separate commit and mark it as *reformatting*/*documentation*. Otherwise GitHub will light up the whole file and people that mostly / only care about the actual program changes will have a hard time finding them.

6. Please don't redo the folder-structure - if you have suggestions for this, just post an issue explaining the benefits of your suggested structure.

Consider making a standalone package!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

We're working on a GitHub-based package manager, much like `npm <https://www.npmjs.com/>`__. Most new functionality from us, such as HTTP and a REST-framework, will come out like separate packages - each with their own repository. This will help keep the IncludeOS core small, and easier to maintain. Clearly, we also want to gather everything in one place, and our upcoming package manager will be doing that. Meanwhile: If you do want make a package - just make it a separate GitHub-repo, and let us know about it. We'll link to it from here, until the package manager is ready.

Issue tracker
~~~~~~~~~~~~~

Post any issues not already mentioned, in the `issue tracker on GitHub <https://github.com/hioa-cs/IncludeOS/issues>`__. You can also post questions not answered by editing the :ref:`FAQ` on GitHub.

Gitter chat
~~~~~~~~~~~

We are usually present in our `public gitter channel <https://gitter.im/hioa-cs/IncludeOS>`__ for any kinds of questions.