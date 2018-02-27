#### crypto-currency

# Biggercoin Core integration/staging tree

https://biggercoin.org

## What is Biggercoin?

_**Biggercoin**_ is a new kind of money on the internet, an effective solution for sending and receiving money with security
and anonymity in your transactions.

_**Biggercoin**_ is a fully decentralized open source payment network without any central authority.

_**Biggercoin**_ offers, in addition to its high security in encryption, more speed for the confirmations of the transactions in
its network Peer to peer, network is that it works totally decentralized, minimizing the attacks of hackers.

For more information, as well as a binary version of the immediately usable _**Biggercoin Core**_ software, see https://biggercoin.org.

## License

The _**Biggercoin Core**_ is released under the terms of the MIT license.

See [COPYING](https://github.com/biggercoin/crypto-currency/blob/master/LICENSE) for more information or see https://opensource.org/licenses/MIT.

## Development Process

Developers work on their own trees and then send shipping requests when they think their feature or bug fix is ready.

The patch will be accepted if there is a broad consensus that it is a good thing. 

Developers should expect to rework and resubmit patches if they do not match the coding conventions of the project (see coding.txt)
or are controversial.

The master branch is regularly built and tested but is not guaranteed to be completely stable. 

Tags are regularly created to indicate new stable version versions of _**Biggercoin**_.

Resource branches are created when there are new major resources being worked on by multiple people.

From time to time, a traction request will be outdated.

If this occurs, and the attraction is no longer automatically combinable; a comment on the attraction will be used to issue a foreclosure notice.

The attraction will be closed 15 days after notice if the action is not taken by the author. 

Request requests closed in this way will have their corresponding question labeled "stagnant".

Noncommittal questions will receive similar notice and will be terminated after 15 days from the last activity.

Questions closed in this way will be labeled "obsolete".

The contribution workflow is described in [CONTRIBUTING.md](http://biggercoin.org).

The developer [mailing list](https://groups.google.com/forum/#!forum/biggercoin) should be used to discuss complicated or controversial changes before working on a set of fixes.

Developer IRC can be found on Freenode at [#_**biggercoin**_](https://webchat.freenode.net).

## Testing

Testing and code review is the development bottleneck; we get more requests to pull than we can review and test soon notice.

Be patient and help by testing other people's traction requests, and keep in mind that this is a critical safety design, where any mistake can cost people a lot of money.

## Automated Testing

Developers are strongly encouraged to write unit tests for the new code and to send new unit tests to the old code.

Unit tests can be compiled and run (assuming they were not disabled in configure) with: make check.

Further details on running and extending drive tests can be found at [/src/test/README.md.](https://groups.google.com/forum/#!forum/biggercoin)

There are also regression and integration tests, written in Python, that run automatically on the build server. 

These tests can be run (if the test dependencies are installed) with: _test /functional / test_runner.py_

The Travis CI system ensures that all traction requests are built for Windows, Linux and OS X and that drive/health tests run automatically.

## Manual Quality Assurance Test (QA)

Changes must be tested by someone other than the developer who wrote the code.

This is especially important for major or high-risk changes.

It is helpful to add a test plan to the traction request description if the change test is not straightforward.

## Translations

We only accept translation corrections that are sent to the [_**Bitcoin Core**_ Transifex page](https://www.transifex.com/bitcoin/bitcoin/). 

Translations are converted into _**Biggercoin**_ periodically.

Translations are periodically removed from Transifex and incorporated into the git repository.

See the translation process for details on how this works.

Important: We do not accept translation changes, since the GitHub routing requests because the next Transifex exit would replace them automatically again.



