# Google Mock

## VERSION

version 1.6

## DESCRIPTION

This is a fork of the [Google mocking framework](https://github.com/google/googlemock).
I use it for my personal testing needs and it turned out 1.6 worked best for me.

## SYNOPSIS

Put this repo as a submodule in your cmake based project.
Then just `target_link_library` against `contrib::gmock` or just `gmock`.

## DEPENDENCIES

gmock depends on [gtest](https://github.com/Drako/gtest).
Simply add that as a submodule as well.
