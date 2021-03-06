.. _contribute:

Contributing to the project
=====================================

PsychoPy is an open-source project. It was originally written by `Jon Peirce`_ to run vision science experiments in his lab. He felt that others might find it useful and made it available by releasing it for free on the web.

Why make it free?
---------------------
It has taken, literally, thousands of hours of programming to get PsychoPy where it is today and it is provided absolutely for free. Without somone working on it full time (which would entail charging you for the result) the only way for the software to keep getting better is if people contribute back to the project.

**Please, please, please** make the effort to give a little back to this project. If you found the documentation hard to understand then think about how you would have preferred it to be written and contribute it.

How do I contribute changes?
-----------------------------
For simple changes, and for users that aren't so confident with things like version control systems then just send your changes to the mailing list as described :ref:`here <mailingList>`.

If you want to make more substantial changes then discuss them on the `developers mailing list <http://groups.google.com/group/psychopy-dev>`_. 

The ideal model, for :ref:`developers` that know about git and may make more frequent contributions, is to :ref:`create your own clone <createClone>` of the project on github, make changes to that and then send a pull request to have them merged back into the main repository.

.. _Jon Peirce: http://www.peirce.org.uk
.. _Sphinx: http://sphinx.pocoo.org

.. _contribForum:

Contribute to the Forum (mailing list)
----------------------------------------------------------
The easiest way to help the project is to write to the forum (mailing list) with suggestions and solutions.

*For documentation suggestions* please try to provide actual replacement text. You, as a user, are probably better placed to write this than the actual developers (they know too much to write good docs)!

*If you're having problems*, e.g. you think you may have found a bug:
    - take a look at the :ref:`troubleshooting` and :ref:`gotchas` first
    - submit a message with as much information as possible about your system and the problem
    - please try to be precise. Rather than say "It didn't work" try to say what what specific form of "not working" you found (did the stimulus not appear? or it appeared but poorly rendered? or the whole application crashed?!)
    - if there is an error message, try to provide it completely
    
*If you had problems* and worked out how to fix things, even if it turned out the problem was your own lack of understanding, please still contribute the information. Others are likely to have similar problems. Maybe the documentation could be clearer, or your email to the forum will be found by others googling for the same problem.

To make your message more useful you should, please try to:
    - provide info about your system and PsychoPy version(e.g. the output of the sysInfo demo in coder). A lot of problems are specific to a particular graphics card or platform
    - provide a minimal example of the breaking code (if you're writing scripts)
    