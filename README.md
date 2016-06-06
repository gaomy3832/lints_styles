# lints_styles
Personalized lint tools and styles

## Contents

* cpplint

  [Google cpplint tool](https://github.com/google/styleguide), cpplint/cpplint.py.

* pylintrc

  Configuration for [pylint](<https://www.pylint.org/).

## Changes

* cpplint

  * Change indent of access keywords to be the same as parent.

  * Change done processing message to stdout.

  * Only output error count when non-zero.

  * Enable `build/include_alpha`.

  * Approve several C++11 headers.

* pylintrc

  * Allow short local variable names.

  * Loose max design size.

