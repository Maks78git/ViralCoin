ViralCoin Core integration/staging tree
https://github.com/Maks78git/ViralCoin
For an immediately usable, binary version of the ViralCoin Core software, check the releases section of this repository.
What is ViralCoin Core?
ViralCoin Core connects to the ViralCoin peer-to-peer network to download and fully validate blocks and transactions. It also includes a wallet and a graphical user interface, which can be optionally built.
Further information about ViralCoin Core is available in the doc folder.
License
ViralCoin Core is released under the terms of the MIT license. See COPYING for more information or visit https://opensource.org/licenses/MIT.
Development Process
The master branch is regularly built (see doc/build-*.md for instructions) and tested, but it is not guaranteed to be completely stable. Tags are created regularly from release branches to indicate new official, stable release versions of ViralCoin Core.
The contribution workflow is described in CONTRIBUTING.md, and useful hints for developers can be found in doc/developer-notes.md.
Testing
Testing and code review is essential for development. We receive more pull requests than we can review and test on short notice, so please be patient and help by testing other people's pull requests. This is a security-critical project where any mistake could impact users significantly.
Automated Testing
Developers are strongly encouraged to write unit tests for new code and to submit new unit tests for old code. Unit tests can be compiled and run (assuming they weren't disabled during the build system generation) with: ctest. Further details on running and extending unit tests can be found in /src/test/README.md.
There are also regression and integration tests, written in Python. These tests can be run (if the test dependencies are installed) with: build/test/functional/test_runner.py (assuming build is your build directory).
The CI (Continuous Integration) systems ensure that every pull request is built for Windows, Linux, and macOS, and that unit/sanity tests are run automatically.
Manual Quality Assurance (QA) Testing
Changes should be tested by someone other than the developer who wrote the code. This is especially important for large or high-risk changes. It is helpful to add a test plan to the pull request description if testing the changes is not straightforward.
Translations
Changes to translations and new translations can be submitted through community contributions. The translation process follows standard localization practices. See the translation process for details on how this works.
Important: We do not accept direct translation changes as GitHub pull requests, as these may be overwritten by automated updates.

