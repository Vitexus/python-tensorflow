# python-tensorflow (Vitexus packaging)

Debian packaging for TensorFlow 2.21 (CPU build). Repackages the official
prebuilt PyPI wheel directly - TensorFlow's own build system (Bazel,
multi-GB, hours-long) is far outside the scope of a simple Debian
packaging pipeline, and Debian's own archive doesn't carry TensorFlow for
exactly this reason.

Packaged for the invokeai-mastodon project's local NSFW image
classification (via opennsfw2's tf-keras backend).
