# wibo 1.2.0 `kernel32!lstrcmpiA` build result

- Workflow: `Build wibo 1.2.0 lstrcmpiA`
- Workflow run ID: `31063528773`
- Pull request: `#2`
- Head commit tested: `a58bab0626f884610b4bea81654e7348801ac093`
- Official upstream tag: `1.2.0`
- Official upstream commit: `c1a7d472bd49e5dbaf3fe9aec272461b2e12f68a`
- Patch SHA-256: `4c9f1b9e3c856ff5b4bc64c20363996310965cfc0d0db419e562ab1cd174fe3f`

## Static Linux i686

- Build: PASS
- Complete CTest suite: 48/48 PASS
- Explicit `wibo.test_lstrcmpi` regression: PASS
- Packaging and artifact upload: PASS
- Binary SHA-256: `d436c2a1cf9eca5ba5289a8d55cf61337de784343e5e2869db5bf78b575bfa8c`
- Actions artifact ZIP SHA-256: `56f45d4e563b88e811213bbe2be6d629f705b1fd4060de1d379bf7468a4de7c9`

## Static Linux x86_64

- Build: PASS
- Complete CTest suite: 48/48 PASS
- Explicit `wibo.test_lstrcmpi` regression: PASS
- Packaging and artifact upload: PASS
- Binary SHA-256: `50ac01b1f0fa6850519ef457ccaf6fc53abb012a1f8586b92b4ef4140e0734a7`
- Actions artifact ZIP SHA-256: `d51ebe059cb93a1475ec94f28925d31d906fb9bc78a3baece0c901567a1e502a`

The i686 and x86_64 artifacts are statically linked ELF executables. The first CI attempt exposed an isolated-container fixture issue in a redundant explicit test rerun; the workflow was corrected to select `wibo.build_fixtures` and `wibo.test_lstrcmpi` together. Run `31063528773` completed successfully for both architectures.
