title: Contributing
---

We welcome you to join the development of ParaView ArcticViewer. This document will help you through the process.

## Before You Start

Please follow the coding style:

- Follow [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript).
- Use soft-tabs with a two space indent.
- Don't put commas first.

## Workflow

1. Fork [kitware/visualizer].
2. Clone the repository to your computer and install dependencies.

    {% code %}
    $ git clone https://github.com/<username>/arctic-viewer.git
    $ cd arctic-viewer
    $ npm install
    $ npm install -g commitizen
    {% endcode %}

3. Create a feature branch.

    {% code %}
    $ git checkout -b new_feature
    {% endcode %}

4. Start hacking.
5. Use Commitizen for commit message

    {% code %}
    $ git cz
    {% endcode %}

6. Push the branch:

    {% code %}
    $ git push origin new_feature
    {% endcode %}

6. Create a pull request and describe the change.

## Updating Documentation

The ParaView ArcticViewer documentation is part of the code repository.

## Reporting Issues

When you encounter some problems when using ParaView ArcticViewer, you can find the solutions in [Troubleshooting](troubleshooting.html) or ask me on [GitHub](https://github.com/kitware/arctic-viewer/issues) or [Mailing list](http://www.paraview.org/mailman/listinfo/paraview). If you can't find the answer, please report it on GitHub.
