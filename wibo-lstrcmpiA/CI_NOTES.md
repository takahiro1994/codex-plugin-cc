# CI validation notes

The build workflow applies the patch to the official wibo 1.2.0 tag and validates both static Linux host architectures.

The dedicated regression rerun selects both `wibo.build_fixtures` and `wibo.test_lstrcmpi` because each Docker invocation starts from the pristine build image.
