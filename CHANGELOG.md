v0.4.0 - February 12, 2014

* 0.4.0 (Nicholas C. Zakas)
* Change: Switch :after to :exit (fixes #605) (Nicholas C. Zakas)
* Fix: Make sure no-unused-vars doesn't get confused by nested functions (fixes #584) (Nicholas C. Zakas)
* Update: .eslintrc to check more things (Nicholas C. Zakas)
* Fix: Make sure JSDoc parser accepts JSDoc3-style optional parameters (Nicholas C. Zakas)
* Docs: Update documentation with linking instructions for ESLintTester (Nicholas C. Zakas)
* New Rule: valid-jsdoc (fixes #536) (Nicholas C. Zakas)
* #595 improved func-names documentation (Kyle Nunery)
* #595 added more func-names tests (Kyle Nunery)
* #595 fix rule message and add more tests (Kyle Nunery)
* use optionator for option parsing, not optimist (George Zahariev)
* Include instructions for working with ESLintTester (Nicholas C. Zakas)
* #595 remove needless 'function Foo() {}' in tests (Kyle Nunery)
* #595 fix whitespace (Kyle Nunery)
* #595 fix markdown for js code blocks (Kyle Nunery)
* Adding information about Yeomen generator (Ilya Volodin)
* #595 add docs for rule func-names (Kyle Nunery)
* #595 add func-names rule (Kyle Nunery)
* migrate variables array to map (Brandon Mills)
* Perf: Move try-catch out of verify() function to allow V8 optimization (refs #574) (Nicholas C. Zakas)
* Docs: Added instructions for running npm run profile (Nicholas C. Zakas)
* refactor variable name lookup into a separate function (Brandon Mills)
* optimize findVariable() in no-unused-vars (Brandon Mills)
* move to tests/bench (Chris Dickinson)
* add `npm run profile`. (Chris Dickinson)
* #586 refactor based on https://github.com/eslint/eslint/pull/590#discussion_r9476367 (Christian)
* #586 added no-unreachable jsdoc, documentation note on hoisting case (Christian)
* #586 add hoisting check to no-unreachable (Christian)
* readme: Remove stray asterisk (Timo Tijhof)
* #580 Remove eslint.getAllComments(), related docs, related tests (Christian)
* Added test for bug fix #582. Test Passes (Shmueli Englard)
* Added curly braces to if statment (Shmueli Englard)
* Added new test for fix to #582 (fixes 582) (Shmueli Englard)
* Bug #582: Added check if node.value isn't a string just exit (Shmueli Englard)
* Update Rule: implement curly options for single-statement bodies (fixes #511) (Nicholas C. Zakas)
* New Rule: no-extra-boolean-cast (fixes #557) (Brandon Mills)
* New Rule: no-sparse-arrays (fixes #499) (Nicholas C. Zakas)
* Fix: no-spaced-func is now an error (Nicholas C. Zakas)
* New Rule: no-process-exit (fixes #568) (Nicholas C. Zakas)
* New Rule: no-labels (fixes #550) (Nicholas C. Zakas)
* New Rule: no-lone-blocks (fixes #512) (Brandon Mills)
* Added Emacs/Flycheck integration (Nikolai Prokoschenko)
* Build: Add perf test (Nicholas C. Zakas)
* Fix: no-cond-assign shouldn't throw error when there's a for loop with an empty conditional (fixes #53) (Nicholas C. Zakas)
* Docs: Add docs for no-regex-spaces and all doc errors now break build (closes #562) (Nicholas C. Zakas)
* Rename: regex-spaces to no-regex-spaces (Nicholas C. Zakas)
* Docs: Add docs for no-underscore-dangle (refs #562) (Nicholas C. Zakas)
* Docs: Add docs for no-undef-init (refs #562) (Nicholas C. Zakas)
* Docs: Add docs for no-return-assign (refs #562) (Nicholas C. Zakas)
* Fix: Misspelling in no-return-assign message (Nicholas C. Zakas)
* Docs: Add docs for no-new-wrappers (refs #562) (Nicholas C. Zakas)
* Docs: Add docs for no-new-object (refs #562) (Nicholas C. Zakas)
* Docs: Add docs for no-implied-eval (refs #562) (Nicholas C. Zakas)
* Docs: Updated documentation for developing rules (Nicholas C. Zakas)
* Testing: Move ESLintTester to be external dependency (fixes #480) (Nicholas C. Zakas)
* Docs: Add list of known integrations (Nicholas C. Zakas)
* Fix #570 (dmp42)
* document no-array-constructor rule (Michael Ficarra)
* fixes #500: no-array-constructor should not flag 1-argument construction (Michael Ficarra)
* fixes #501: no-array-constructor recognises CallExpression form (Michael Ficarra)
* rename no-new-array rule to no-array-constructor; ref #501 (Michael Ficarra)
* Fix: Make radix rule warn on invalid second parameter (fixes #563) (Nicholas C. Zakas)
* Docs: Added no-floating-decimal docs (refs #562) (Nicholas C. Zakas)
* New Rule: no-path-concat (fixes #540) (Nicholas C. Zakas)
* Docs: Add some missing rule docs (refs #562) (Nicholas C. Zakas)
* Fix: CLI should not output anything when there are no warnings (fixes #558) (Nicholas C. Zakas)
* New Rule: no-yoda (fixes #504) (Nicholas C. Zakas)
* New Rule: consistent-return (fixes #481) (Nicholas C. Zakas)
* Rewrite configuration documentation to include information about globals (fixes #555) (Nicholas C. Zakas)
* Allow YAML configuration files (fixes #491) (Nicholas C. Zakas)
* 0.3.0 (Nicholas C. Zakas)

v0.3.0 - January 20, 2014

* 0.3.0 (Nicholas C. Zakas)
* Config: Allow comments in JSON configuration files (fixes #492) (Nicholas C. Zakas)
* Bug: max-len fix to report correct line number (fixes #552) (Nicholas C. Zakas)
* Build: Use browserify to create browser-ready ESLint (fixes #119) (Nicholas C. Zakas)
* Docs: Ensure all rules have entry on top-level rules index page (Nicholas C. Zakas)
* Docs: Add docs for no-fallthrough rule (Nicholas C. Zakas)
* Update README.md (Peter deHaan)
* Update README.md (Peter deHaan)
* Update package.json (Peter deHaan)
* Docs: Added documentation for semi rule (Nicholas C. Zakas)
* Build: Reset branch coverage target (Nicholas C. Zakas)
* Update build system to generate eslint.org during release (Nicholas C. Zakas)
* Updated setup doc (Nicholas C. Zakas)
* Fix #525 & #528 (Mangled Deutz)
* Improve no-negated-in-lhs description (David Bruant)
* Fixing typo (David Bruant)
* Update no-new.md (Tamas Fodor)
* Update no-extra-semi.md (Tamas Fodor)
* Fixing broken links in documentation (Ilya Volodin)
* Update about page (Nicholas C. Zakas)
* Site generation build step and documentation updates to support it (fixes #478) (Nicholas C. Zakas)
* Change message for brace-style rule (fixes #490) (Nicholas C. Zakas)
* Add question about ES6 support to FAQ (fixes #530) (Nicholas C. Zakas)
* Set unlimited number of listeners for event emitter (fixes #524) (Nicholas C. Zakas)
* Add support for comment events (fixes #531) Add :after events for comments (Nicholas C. Zakas)
* Add :after events for comments (Nicholas C. Zakas)
* Allow config files to have any name (fixes #486). (Aparajita Fishman)
* List available formatters (fixes #533). (Aparajita Fishman)
* Add support for comment events (fixes #531) (Nicholas C. Zakas)
* Add Stylish formatter and make it default. Fixes #517 (Sindre Sorhus)
* Fix missing code exit (Mangled Deutz)
* Added unit test for calling Config.getConfig with no arguments. (Aparajita Fishman)
* Typo (Mangled Deutz)
* Fixed docs typo (Nicholas C. Zakas)
* Mark functions as used when any method is called on them (Nicholas C. Zakas)
* Fixed: Config.getConfig is called either with a file path or with no args (fixes #520) (Aparajita Fishman)
* Fix minor bug in no-empty rule (Nicholas C. Zakas)
* add more info for failure messages (Nicholas C. Zakas)
* Add ruleId to all formatters output (fixes #472) (Nicholas C. Zakas)
* Remove unused code (Nicholas C. Zakas)
* Correctly handle case with both finally and catch in no-empty (Nicholas C. Zakas)
* Update documentation for no-unused-vars (Nicholas C. Zakas)
* Ensure that bound function expressions are reported as being used (fixes #510) (Nicholas C. Zakas)
* Allow empty catch/finally blocks (fixes #514) and update documentation (fixes #513) (Nicholas C. Zakas)
* Updated contribution guidelines (Nicholas C. Zakas)
* Add default setting for no-cond-assign (Nicholas C. Zakas)
* Add build step to check rule consistency (Nicholas C. Zakas)
* update docs: explicit cli args are exempt from eslintignore exclusions (Michael Ficarra)
* fixes #505: no-cond-assign should ignore doubly parenthesised tests (Michael Ficarra)
* Renamed unnecessary-strict to no-extra-strict (Nicholas C. Zakas)
* Fixed missing documentation links (Nicholas C. Zakas)
* Add build task to check for missing docs and tests for rules (Nicholas C. Zakas)
* Slight reorganization of rule groups (Nicholas C. Zakas)
* Added one-var and sorted some rules (Nicholas C. Zakas)
* Updated Travis badge for new location (Nicholas C. Zakas)
* fixes #494: allow shebangs in processed JS files (Michael Ficarra)
* fixes #496: lint ignored files when explicitly specified via the CLI (Michael Ficarra)
* More tests (Ilya Volodin)
* Upgrade Istanbul (Ilya Volodin)
* fixes #495: holey arrays cause no-comma-dangle rule to throw (Michael Ficarra)
* Documentation and minor changes (Ilya Volodin)
* Adding missing package registration (Ilya Volodin)
* Adding support for .eslintignore and .jshintignore (Closes #484) (Ilya Volodin)
* fixes #482: brace-style bug with multiline conditions (Michael Ficarra)
* Switching Travis to use ESLint (Closes #462) (Ilya Volodin)
* 0.2.0 (Nicholas C. Zakas)

v0.2.0 - January 1, 2014

* 0.2.0 (Nicholas C. Zakas)
* Bump code coverage checks (Nicholas C. Zakas)
* Take care of unreachable code in case statement (Nicholas C. Zakas)
* Updated rule messaging and added extra tests (Nicholas C. Zakas)
* Fixing eslint errors and unittests (Ilya Volodin)
* Rule: max-nested-callbacks (Ian Christian Myers)
* Fix fall-through rule with nested switch statements (fixes #430) (Nicholas C. Zakas)
* Fixed trailing comma (Nicholas C. Zakas)
* Added more tests for func-style (Nicholas C. Zakas)
* Fixed documentation for func-style (Nicholas C. Zakas)
* Fixed linting error (Nicholas C. Zakas)
* Rule to enforce function style (fixes #460) (Nicholas C. Zakas)
* Rule is off by default. Updated documentation (Ilya Volodin)
* Rule: sort variables. Closes #457 (Ilya Volodin)
* Update architecture.md (Nicholas C. Zakas)
* Change quotes option to avoid-escapes and update docs (fixes #199) (Brandon Payton)
* Add allow-avoiding-escaped-quotes option to quotes rule (fixes #199) (Brandon Payton)
* Update no-empty-class.md (Nicholas C. Zakas)
* Updated titles on all rule documentation (fixes #348) (Nicholas C. Zakas)
* Fixing eslint errors in codebase (Ilya Volodin)
* fixes #464: space-infix-ops checks for VariableDeclarator init spacing (Michael Ficarra)
* Add options to no-unused-vars. Fixes #367 (Ilya Volodin)
* rename escape function to xmlEscape in checkstyle formatter (Michael Ficarra)
* The semi rule now reports correct line number (Ian Christian Myers)
* context.report now takes optional location (Ian Christian Myers)
* fixes #454: escape values for XML in checkstyle formatter (Michael Ficarra)
* Add color to Mocha test reporting (Ian Christian Myers)
* Rule no-nested-ternary (Ian Christian Myers)
* Fixing no-unused-var and no-redeclare (Ilya Volodin)
* fixes #449: no-mixed-requires throws TypeError when grouping is enabled (Michael Ficarra)
* Fixed reported line number for trailing comma error (Ian Christian Myers)
* Update doc title for quote (Matthew DuVall)
* fixes #446: join paths without additional delimiters (Michael Ficarra)
* docs: add documentation for quotes rule (Matthew DuVall)
* minor style changes to lib/rules/space-infix-ops.js as requested in #444 (Michael Ficarra)
* remove "function invalid(){ return D }" from some tests (Michael Ficarra)
* fixes #429: require spaces around infix operators; enabled by default (Michael Ficarra)
* simplify fix for #442 (Michael Ficarra)
* Fix broken test, ensure tests get run before a release is pushed (Nicholas C. Zakas)
* 0.1.4 (Nicholas C. Zakas)

v0.1.4 - December 5, 2013

* 0.1.4 (Nicholas C. Zakas)
* Add release scripts to package.json (Nicholas C. Zakas)
* Fixed release error in Makefile (Nicholas C. Zakas)
* Fix JSHint warnings (Nicholas C. Zakas)
* Make sure 'default' isn't flagged by no-space-returns-throw rule (fixes #442) (Nicholas C. Zakas)
* Fixing documentation (Ilya Volodin)
* Fixing disabling rules with invalid comments Closes #435 (Ilya Volodin)
* improve assertion on wrong number of errors (Christoph Neuroth)
* fixes #431: no-unused-expressions should not flag statement level void (Michael Ficarra)
* fixes #437: fragile no-extend-native rule (Michael Ficarra)
* change space-* rule documentation headers to be more descriptive (Michael Ficarra)
* Moved to tabs, added comments, a few more tests (Jamund Ferguson)
* split GH-332 rule into space-unary-word-ops and space-return-throw-case (Michael Ficarra)
* fixes #346: validate strings passed to the RegExp constructor (Michael Ficarra)
* change some documentation extensions from js to md (Michael Ficarra)
* fixes #332: unary word operators must be followed by whitespace (Michael Ficarra)
* Add some docs (Jamund Ferguson)
* DRYing cli tests and improving code coverage (Ilya Volodin)
* fixes #371: add no-shadow-restricted-names rule (Michael Ficarra)
* Added Support for Object.defineProperty() checking (Jamund Ferguson)
* fixes #333: add rule to disallow gratuitously parenthesised expressions (Michael Ficarra)
* improve rule test coverage (Michael Ficarra)
* No Extend Native (Jamund Ferguson)
* change getTokens 2nd/3rd arguments to count tokens, not characters (Michael Ficarra)
* fixes #416: no-fallthrough flagging last case + reporting wrong line num (Michael Ficarra)
* fixes #415: fix unnecessary-strict rule false positives (Michael Ficarra)
* Add missing dependency (Nicholas C. Zakas)
* Update docs related to running unit tests (Nicholas C. Zakas)
* Add JSHint as missing dependency (Nicholas C. Zakas)
* Switch to using ShellJS makefile (fixes #418) (Nicholas C. Zakas)
* Updated documentation to reflect test changes (refs #417) (Nicholas C. Zakas)
* Change to eslintTester.addRuleTest (fixes #417) (Nicholas C. Zakas)
* Fix false positives for no-script-url (fixes #400) (Nicholas C. Zakas)
* Fix lint warning (Nicholas C. Zakas)
* Fixing ESLint warnings, introducing Makefile.js (not yet wired in) (Nicholas C. Zakas)
* fixes #384: include builtin module list to avoid repl dependency (Michael Ficarra)
* 0.1.3 (Nicholas C. Zakas)

v0.1.3 - November 25, 2013

* 0.1.3 (Nicholas C. Zakas)
* Updated changelog (Nicholas C. Zakas)
* Vows is gone. Mocha is now default (Ilya Volodin)
* fixes #412: remove last remaining false positives in no-spaced-func (Michael Ficarra)
* fixes #407: no-spaced-func rule flagging non-argument-list spaced parens (Michael Ficarra)
* Add no-extra-semi to configuration (fixes #386) (Nicholas C. Zakas)
* Converting formatter tests and core (Ilya Volodin)
* Don't output anything when there are no errors in compact formatter (fixes #408) (Nicholas C. Zakas)
* Removing Node 0.11 test - it fails all the time (Nicholas C. Zakas)
* Completing conversion of rule's tests to mocha (Ilya Volodin)
* added mocha conversion tests for strict, quote-props and one-var; enhanced one of the invalid one-var tests that was expecting two messages (Michael Paulukonis)


v0.1.2 - November 23, 2013

* 0.1.2 (Nicholas C. Zakas)
* added mocha tests for radix and quotes; fixed some of the internals on quotes from vows annotations (Michael Paulukonis)
* added tests for regex-spaces, strict, unnecessary-strict; fixed some types in overview/author notes in other tests. (Michael Paulukonis)
* Converting unittests to mocha (Ilya Volodin)
* mocha conversions of tests for 'use-isnan' and 'wrap-iife' (Michael Paulukonis)
* added mocha tests semi.js and wrap-regex.js (Michael Paulukonis)
* Converting more tests to mocha (Ilya Volodin)
* Update CONTRIBUTING.md (Nicholas C. Zakas)
* Cleaning up eslintTester (Ilya Volodin)
* DRYing unittests and converting them to mocha (Ilya Volodin)
* Reformatted Gruntfile (Nicholas C. Zakas)
* Add tests to config load order: base, env, user. (icebox)
* Fixing indent in gruntfile (Ilya Volodin)
* Removing jake, adding Grunt, Travis now runs grunt (Ilya Volodin)
* Add rules per environments to config. (icebox)
* Add globals property to the environments. (icebox)
* Fix error about IIFE if the function is in a new (Marsup)
* Fix a broken link in the docs (Brian J Brennan)
* Add test coverage for additional cases, fix open paren at beginning of expr (Matthew DuVall)
* Fixing no-undef for eval use case (Ilya Volodin)
* fixes #372: disallow negated left operand in `in` operator (Michael Ficarra)
* Fixing no-self-compare rule to check for operator (Ilya Volodin)
* bug: open parens in args causes no-spaced-func to trigger (Matthew DuVall)
* fixes #369: restrict UnaryExpressions to delete in no-unused-expressions (Michael Ficarra)
* Make sure delete operator isn't flagged as unused expression (fixes #364) (Nicholas C. Zakas)
* Don't flag ++ or -- as unused expressions (fixes #366) (Nicholas C. Zakas)
* Ensure that 'use strict' isn't flagged as an unused expression (fixes #361) (Nicholas C. Zakas)
* Increase test coverage for strict-related rules (refs #361) (Nicholas C. Zakas)
* Up code coverage numbers (Nicholas C. Zakas)
* Fixes error in new-cap rule when 'new' is used without a constructor (fixes #360) (Nicholas C. Zakas)
* added files array in package json (Christian)
* removed unused jshint dependency (Christian)
* Add test coverage for new Foo constructor usage (Matt DuVall)
* Pull code coverage up by removing unused method (Matt DuVall)
* recognise CallExpression variant of RegExp ctor in no-control-regex rule (Michael Ficarra)
* Merge smart-eqeqeq into eqeqeq (Matt DuVall)
* Catch additional cases for a.b, new F, iife (Matt DuVall)
* 0.2.0-dev (Nicholas C. Zakas)
* Version 0.1.0 (Nicholas C. Zakas)
* rule: no-spaced-func disallow spaces between function identifier and application (Matt DuVall)

v0.1.1 - November 09, 2013

* Ensure mergeConfigs() doesn't thrown an error when keys are missing in base config (fixes #358) (Nicholas C. Zakas)

v0.1.0 - November 03, 2013

* Version 0.1.0 (Nicholas C. Zakas)
* Updated Readme for v0.1.0 (Nicholas C. Zakas)
* Bump code coverage verification to 95% across the board (Nicholas C. Zakas)
* Fixed broken links (Nicholas C. Zakas)
* Added information about runtime rules (Nicholas C. Zakas)
* Added documentation about configuration files (Nicholas C. Zakas)
* Added description of -v option (Nicholas C. Zakas)
* Updated architecture documentation (Nicholas C. Zakas)
* Fix bug in no-control-regex (fixes #347) (Nicholas C. Zakas)
* Fix link to architecture doc in readme (azu)
* Rule: No control characters in regular expressions (fixes #338) (Nicholas C. Zakas)
* Add escaping \= test (Matt DuVall)
* Add docs for rule (Matt DuVall)
* rule: no-div-regex for catching ambiguous division operators in regexes (Matt DuVall)
* Change context-var to block-scoped-var (Matt DuVall)
* Implement config.globals (Oleg Grenrus)
* Add 'config-declared global' test (Oleg Grenrus)
* Adding ability to separate rules with comma (Ilya Volodin)
* Added rule for missing 'use strict' (fixes #321) (Nicholas C. Zakas)
* Fixing unittests and finishing code (Ilya Volodin)
* Disabling/enabling rules through comments (Ilya Volodin)
* Rename rule to context-var and add documentation (Matt DuVall)
* Added link to no-global-strict doc in readme (Nicholas C. Zakas)
* Add try-catch scoping with tests (Matt DuVall)
* Fix linting error (Matt DuVall)
* Store FunctionDeclarations in scope as they can be used as literals (Matt DuVall)
* Fix to use getTokens and add test for MemberExpression usage (Matt DuVall)
* rule: block-scope-var to check for variables declared in block-scope (Matt DuVall)
* no-unused-expressions rule: add test and doc mention for `a && b()` (Michael Ficarra)
* rule: wrap-regex for parens around regular expression literals (Matt DuVall)
* fixes #308: implement no-unused-expressions rule; ref. jshint rule W030 (Michael Ficarra)
* Updated change log script to filter out merge messages (Nicholas C. Zakas)
* Updated changelog (Nicholas C. Zakas)
* 0.1.0-dev (Nicholas C. Zakas)

v0.0.9 - October 5, 2013

* Version 0.0.9 release (Nicholas C. Zakas)
* Added rule for no global strict mode (fixes #322) (Nicholas C. Zakas)
* Change default on to be errors instead of warnings (fixes #326) (Nicholas C. Zakas)
* Fixed bug where JSHint was using the wrong file in lint task (Nicholas C. Zakas)
* Updated docs for no-unused vars rule. (Andrew de Andrade)
* Removed console.log in tests. (Andrew de Andrade)
* Added link to roadmap and JSHint feature parity list. (Andrew de Andrade)
* Fixed warning when unused var declared as param in FunctionExpression/Declaration can be ignored because later param is used (Andrew de Andrade)
* Rename test for smartereqeqeq.js to smarter-eqeqeq.js (Andrew de Andrade)
* Keep test filename inline with rule name (Andrew de Andrade)
* Added further instructions for multiline test cases. (Andrew de Andrade)
* Protecting private method (Seth McLaughlin)
* Updating look up algorithm for local config files (Seth McLaughlin)
* Fixing ESLint errors (Ilya Volodin)
* Implemented local default config file (Seth McLaughlin)
* Upgrading escope version and fixing related bugs (Ilya Volodin)
* Fixing assignment during initialization issue (Ilya Volodin)
* add plain-English regexp description to no-empty-class rule (Michael Ficarra)
* fixes #289: no-empty-class flags regexps with... flags (Michael Ficarra)
* Rule: no-catch-shadow (Ian Christian Myers)
* Update no-empty for compatibility with esprima@1.0.4 (fixes #290) (Mark Macdonald)
* Fixing bug with _ in MemberExpression (Ilya Volodin)
* Rule: no-func-assign (Ian Christian Myers)
* Fix false warning from no-undef rule (fixes #283) (Mark Macdonald)
* Adding eslint to jake (Ilya Volodin)
* Rule no redeclare (Ilya Volodin)
* Fixing no use before define issues (Ilya Volodin)
* Rule: no-octal-escape (Ian Christian Myers)
* Fix for `no-proto` and `no-iterator` false positive (Ian Christian Myers)
* Rule: no-iterator (Ian Christian Myers)
* Fixing type in guard-for-in documentation (Ilya Volodin)
* Rule No use before define (Ilya Volodin)
* Added documentation for the `no-new` rule (Ian Christian Myers)
* Added documentation for the `no-eval` rule (Ian Christian Myers)
* Added documentation for the `no-caller` rule (Ian Christian Myers)
* Added documentation for the `no-bitwise` rule (Ian Christian Myers)
* simplify no-empty-class rule (Michael Ficarra)
* Fix `no-empty-class` false negatives (Ian Christian Myers)
* Added documentation for the `no-alert` rule (Ian Christian Myers)
* Added documentation for the `new-parens` rule (Ian Christian Myers)
* Added documentation for the `max-params` rule (Ian Christian Myers)
* Added documentation for `max-len` rule (Ian Christian Myers)
* Created link from rules README.md to no-plusplus.md documentation (Ian Christian Myers)
* Added documentation for `guard-for-in` rule (Ian Christian Myers)
* Added documentation for `dot-notation` rule (Ian Christian Myers)
* Added documentation for `curly` rule (Ian Christian Myers)
* Updated `camelcase` rule documentation (Ian Christian Myers)
* Added documentation for `complexity` rule (Ian Christian Myers)
* Changed `no-dangle` documentation to `no-comma-dangle` (Ian Christian Myers)
* Rule: no-empty-class (Ian Christian Myers)
* Increased test coverage for max-depth (Ian Christian Myers)
* Increased test coverage for no-shadow (Ian Christian Myers)
* Increased test coverage on no-mixed-requires (Ian Christian Myers)
* Added docs for eqeqeq and no-with (fixes #262) (Raphael Pigulla)
* Create camelcase.md (Micah Eschbacher)
* Fix issues with function in no-unused-vars (Ilya Volodin)
* Rule: No shadow (Ilya Volodin)
* fixes #252: semi rule errors on VariableDeclarations in ForInStatements (Michael Ficarra)
* rule: max-len to lint maximum length of a line (Matt DuVall)
* Fixes #249 (Raphael Pigulla)
* Merge branch 'master' of https://github.com/beardtwizzle/eslint (Jonathan Mahoney)
* Re-add lines that were accidentally deleted from config (Jonathan Mahoney)
* Add support for pre-defined environment globals (re: #228) (Jonathan Mahoney)
* Rule: no-else-return (Ian Christian Myers)
* Re-add lines that were accidentally deleted from config (Jonathan Mahoney)
* Add support for pre-defined environment globals (re: #228) (Jonathan Mahoney)
* Fix no-unused-vars to report correct line numbers (Ilya Volodin)
* Rule: no proto (Ilya Volodin)
* Rule: No Script URL (Ilya Volodin)
* Rule: max-depth (Ian Christian Myers)
* Fix: Error severity for rules with options. (Ian Christian Myers)
* Rule: No wrap func (Ilya Volodin)
* bug: Fixes semi rule for VariableDeclaration in ForStatement (Matt DuVall)
* Individual perf tests for rules (Ilya Volodin)
* Fix loading rules from a rules directory (Ian Christian Myers)
* Rule no-mixed-requires (fixes #221) (Raphael Pigulla)
* bug: Add ForStatement for no-cond-assign check (Matthew DuVall)
* JSLint XML formatter now escapes special characters in the evidence and reason attributes. (Ian Christian Myers)
* Formatter: JSLint XML (Ian Christian Myers)
* Refactored `max-statements` rule. (Ian Christian Myers)
* Fix tests broken due to new rule message text (James Allardice)
* Merge branch 'master' into match-jshint-messages (James Allardice)
* Refactored `one-var` rule. (Ian Christian Myers)
* split eslint.define into eslint.defineRule and eslint.defineRules (Michael Ficarra)
* Removed unnecessary rules.js test. (Ian Christian Myers)
* Rule: one-var (Ian Christian Myers)
* Rule: No unused variables (Ilya Volodin)
* expose interface for defining new rules at runtime without fs access (Michael Ficarra)
* disallow 00 in no-octal rule (Michael Ficarra)
* Increased test coverage for `lib/cli.js`. (Ian Christian Myers)
* Increased test coverage for `lib/rules.js` (Ian Christian Myers)
* Increased test coverage for jUnit formatter. (Ian Christian Myers)
* scripts/bundle: output bundle+map to /build directory (Michael Ficarra)
* add test for 0X... hex literals in no-octal tests (Michael Ficarra)
* fixes #200: no-octals should not see leading-0 floats as violations (Michael Ficarra)
* add back tests for loading rules from a directory (Michael Ficarra)
* add back in ability to load rules from a directory (Michael Ficarra)
* Increased test coverage for `complexity` rule. (Ian Christian Myers)
* Increased test coverage for `max-params` rule. (Ian Christian Myers)
* also output source map when generating bundle (Michael Ficarra)
* Rule: unnecessary-strict (Ian Christian Myers)
* Improve performance of getTokens (Ilya Volodin)
* Performance jake task (Ilya Volodin)
* don't force explicit listing of rules; generate listing for bundle (Michael Ficarra)
* Rule: no-dupe-keys (Ian Christian Myers)
* fixes #145: create a browser bundle (Michael Ficarra)
* Fixing no-caller bug (Ilya Volodin)
* Check for use of underscore library as an exception for var declarations (Matthew DuVall)
* Merge branch 'master' of https://github.com/nzakas/eslint into no-underscore-dangle (Matthew DuVall)
* Fixing spelling (Ilya Volodin)
* Rule: no-empty-label (Ilya Volodin)
* Add builtin globals to the global scope (fixes #185) (Mark Macdonald)
* Rule: no-loop-func (Ilya Volodin)
* Merge branch 'master' of https://github.com/nzakas/eslint into no-underscore-dangle (Matt DuVall)
* Use proper node declarations and __proto__ exception (Matt DuVall)
* Updating no-undef patch (see pull request #164) * Simplify parseBoolean() * Make knowledge of```/*jshint*/``` and ```/*global */``` internal to eslint object * Put user-declared globals in Program scope (Mark Macdonald)
* Rule: no-eq-null (Ian Christian Myers)
* fixed broken merge (Raphael Pigulla)
* fixes #143 (Raphael Pigulla)
* added consistent-this rule (Raphael Pigulla)
* Rule: no-sync to encourage async usage (Matt DuVall)
* Update eslint.json with no-underscore-dangle rule (Matt DuVall)
* Rule: no-underscore-dangle for func/var declarations (Matt DuVall)
* Warn on finding the bitwise NOT operator (James Allardice)
* Updating no-undef patch (see pull request #164) 3. Move parsing of ```/*global */``` and ```/*jshint */``` to eslint.js (Mark Macdonald)
* Warn on finding a bitwise shift operator (fixes #170) (James Allardice)
* Fix broken test (James Allardice)
* Add support for the do-while statement to the curly rule (closes #167) (James Allardice)
* Removing nasty leading underscores (Patrick Brosset)
* Added tests and test cases for a few files (Patrick Brosset)
* CLI: -f now accepts a file path (Ian Christian Myers)
* Updating no-undef patch (see pull request #164) 1. Move predefined globals to ```conf/environments.json``` 2. Move mixin() to ```lib/util.js``` (Mark Macdonald)
* Match messages to JS[LH]int where appropriate, and ensure consistent message formatting (closes #163) (James Allardice)
* Add support for the do-while statement to the curly rule (closes #167) (James Allardice)
* Removing nasty leading underscores (Patrick Brosset)
* Added tests and test cases for a few files (Patrick Brosset)
* Merge branch 'master' of github.com:nzakas/jscheck (Nicholas C. Zakas)
* Added acceptance criteria for rules to docs (Nicholas C. Zakas)
* Add no-undef (fixes #6) (Mark Macdonald)
* Fixing no-self-compare (Ilya Volodin)
* Rule: No multiline strings (Ilya Volodin)
* CLI refactor to remove process.exit(), file not found now a regular error message, updated formatters to handle this case (Nicholas C. Zakas)
* Rule: no-self-compare (Ilya Volodin)
* Rule: No unnecessary semicolons (fixes #158) (Nicholas C. Zakas)
* Fixed error in no-ex-assign when return statement as found in catch clause (Nicholas C. Zakas)
* Rename no-exc-assign to no-ex-assign and add to config (Nicholas C. Zakas)
* Renamed count-spaces to regex-spaces (Nicholas C. Zakas)
* Documentation updates (Nicholas C. Zakas)
* Put all rules into strict mode and update docs accordingly (Nicholas C. Zakas)
* Merge branch 'master' of github.com:nzakas/jscheck (Nicholas C. Zakas)
* Ensure getScope() works properly when called from Program node (fixes #148) (Nicholas C. Zakas)
* Rule: wrap-iife (Ilya Volodin)
* add additional test for no-cond-assign rule (Stephen Murray)
* Merge branch 'master' of github.com:nzakas/jscheck (Nicholas C. Zakas)
* Experimental support for Jake as a build system (fixes #151) (Nicholas C. Zakas)
* fixes #152 (Stephen Murray)
* add docs for no-exc-assign (Stephen Murray)
* Merge branch 'master' of https://github.com/nzakas/eslint into no-new-object-array-literals (Matt DuVall)
* Merge branch 'master' of https://github.com/nzakas/eslint into count-spaces (Matt DuVall)
* Added a test for getting global scope from Program node (refs #148) (Nicholas C. Zakas)
* Add positive test case for <object>.Array (Matthew DuVall)
* Only support space characters for repetitions (Matthew DuVall)
* fix line length per code conventions (Stephen Murray)
* fix indentation per code conventions (Stephen Murray)
* fixes #149 (Stephen Murray)
* Rule: no-ternary (Ian Christian Myers)
* Check that the return statement has an argument before checking its type (James Allardice)
* Rule: count-spaces for multiple spaces in regular expressions (Matt DuVall)
* Update eslint.json configuration file for literal rules (Matt DuVall)
* Created no-label-var rule. (Ian Christian Myers)
* Rule: no-new-array and no-new-object (Matt DuVall)
* Added ability to retrieve scope using escope. (Ian Christian Myers)
* Corrected unused arguments (Patrick Brosset)
* Reporting function complexity on function:after and using array push/pop to handle nesting (Patrick Brosset)
* Fixing style issues discovered while npm testing (Patrick Brosset)
* First draft proposal for a cyclomatic complexity ESLint rule (Patrick Brosset)
* Corrected file extension on no-plusplus rule documentation. (Ian Christian Myers)
* Documentation for no-delete-var rule. Closes #129 (Ilya Volodin)
* Rule: max-statements (Ian Christian Myers)
* Better documentation for the `no-plusplus` rule. (Ian Christian Myers)
* Rule: no-plusplus (Ian Christian Myers)
* Rule: no assignment in return statement (Ilya Volodin)
* Updating max-params rule name (Ilya Volodin)
* Rule: Function has too many parameters (Ilya Volodin)
* Removing merge originals (Ilya Volodin)
* Rebasing on master (Ilya Volodin)
* Rule: Variables should not be deleted (Ilya Volodin)
* Fixes incorrect reporting of missing semicolon (Ian Christian Myers)
* Rebase against master branch (Mathias Bynens)
* Rule to warn on use of Math and JSON as functions (James Allardice)
* Formatter: Checkstyle (Ian Christian Myers)
* docs: Clean up structure (Mathias Bynens)
* Merging no-native-reassign and no-redefine (Ilya Volodin)
* Rule: no native reassignment (Ilya Volodin)
* 0.0.8-dev (Nicholas C. Zakas)
* v0.0.7 released (Nicholas C. Zakas)
* Updated Tests, etc. (Jamund Ferguson)
* Added jUnit Support (Fixes #16) (Jamund Ferguson)

v0.0.7 - July 22, 2013

* 0.0.7 (Nicholas C. Zakas)
* Add code coverage checks to npm test and update rule tests to have better coverage (Nicholas C. Zakas)
* Fixed CLI output on serial programatic executions (Ian Christian Myers)
* Removes line length from code style convention docs (Josh Perez)
* Adds escapeRegExp and fixes documentation (Josh Perez)
* Add quotes rule and test coverage for configuration options (Matt DuVall)
* Adds templating for lint messages and refactors rules to use it (Josh Perez)
* Fixes lint rules for unchecked test file (Josh Perez)
* Changes dotnotation rule to match JSHint style (Josh Perez)
* Change configInfo to options and add test coverage (Matt DuVall)
* Merge branch 'master' of https://github.com/nzakas/eslint into optional-args-for-rule (Matt DuVall)
* Adds dot notation lint rule (Josh Perez)
* Strip trailing underscores in camelcase rule - Fixes #94 (Patrick Brosset)
* add mailing list link (Douglas Campos)
* Strip leading underscores in camelcase rule - Fixes #94 (Patrick Brosset)
* Created no-dangle rule. (Ian Christian Myers)
* Fixed rule name (James Allardice)
* Make sure the callee type is Identifier (James Allardice)
* Add rule for implied eval via setTimeout/Interval (James Allardice)
* Fix rule name in config (James Allardice)
* Fixes #90 -- updates docstrings (Stephen Murray)
* Fixes issue with fs.existsSync on NodeJS 0.6 (Ian Christian Myers)
* Fixing -c config option. (Ian Christian Myers)
* Allow arrays to be passed as multiple args to rule (Matt DuVall)
* Test to make sure empty case with one line break is safe (Matt DuVall)
* Rule: The Function constructor is eval (Ilya Volodin)
* Enabled require("eslint") and exposed out CLI. (Ian Christian Myers)
* Adds test and fix for issue #82 (Mark Macdonald)
* Merge branch 'master' of https://github.com/nzakas/eslint into ok (Yusuke Suzuki)
* Created brace-style rule. (Ian Christian Myers)
* Formatters can now process multiple files at once (Jamund Ferguson)
* Rule: Do not use 'new' for side effects (Ilya Volodin)
* Adds smarter-eqeqeq rule (Josh Perez)
* Add EditorConfig file for consistent editor/IDE behavior (Jed Hunsaker)
* Fix the positive case for no-unreachable where there is no return statement at all, or if the return is at the end. Those cases should not return any errors. The error condition was not be checked before throwing the rule error. (Joel Feenstra)
* Adds test and fix for no-octal on 0 literal (Mark Macdonald)
* Don't report no-empty warnings when a parent is FunctionExpression / FunctionDeclaration (Yusuke Suzuki)
* Add api.getAncestors (Yusuke Suzuki)
* Ensure estraverse version 1.2.0 or later (Yusuke Suzuki)
* Fixes no-alert lint rule for non identifier calls (Josh Perez)
* Fixes exception when init is null (Josh Perez)
* Fixes no-octal check to only check for numbers (Josh Perez)
* 0.0.7-dev (Nicholas C. Zakas)
* 0.0.6 (Nicholas C. Zakas)
* Follow the rule naming conventions (James Allardice)
* Add rule for missing radix argument to parseInt (James Allardice)
* Allow return, falls-through comment, and throw for falls-through (Matt DuVall)
* Merge branch 'master' of https://github.com/nzakas/eslint into rule-fall-through (Matt DuVall)
* Globals are not good, declare len (Matt DuVall)
* Rule to add no-fall-through (Matt DuVall)

v0.0.6 - July 16, 2013

* 0.0.6 (Nicholas C. Zakas)
* Changed semi rule to use tokens instead of source (Nicholas C. Zakas)
* Renaming new-parens rule (Ilya Volodin)
* Renaming no-new-wrappers rule and adding tests (Ilya Volodin)
* Add license URL (Nick Schonning)
* Remove unused sinon requires (Nick Schonning)
* Remove redundant JSHint directives (Nick Schonning)
* Rule: Do not use constructor for wrapper objects (Ilya Volodin)
* Test node 0.11 unstable but allow it to fail (Nick Schonning)
* Rule: Constructor should use parentheses (Ilya Volodin)
* Fix reference to "CSS Lint" in Contributing documentation (Brian McKenna)
* Add git attributes file for line endings (Andy Hu)
* Rename to create an 'index' file in GH web view (Evan Goer)
* Avoid accidentally creating a markdown link (Evan Goer)
* Add headings and correct internal links (Evan Goer)
* Add wiki files to docs directory (Evan Goer)
* Add rules for leading/trailing decimal points (James Allardice)
* Add rule to prevent comparisons with value NaN (James Allardice)
* Fixing jshint error (Ilya Volodin)
* Rule: no octal literals (Ilya Volodin)
* Rule: no undefined when initializing variables (Ilya Volodin)
* Updated CONTRIBUTING.md (Nicholas C. Zakas)
* Make sure namespaces are honored in new-cap (Nicholas C. Zakas)
* Make sure no-empty also checks for ';;' (Nicholas C. Zakas)
* Add CLI option to output version (Nicholas C. Zakas)
* Updated contribution guidelines (Nicholas C. Zakas)
* Fixing jshint complaints. (Joel Feenstra)
* Converting to a switch statement and declaring variables. (Joel Feenstra)
* Added .jshintrc file (until ESLint can lint itself) and cleaned up JSHint warnings (Nicholas C. Zakas)
* Merge branch 'master' of github.com:nzakas/jscheck (Nicholas C. Zakas)
* A bit of cleanup (Nicholas C. Zakas)
* Add unreachable code detection for switch cases and after continue/break. (Joel Feenstra)
* Add support for detecting unreachable code after a throw or return statement. (Joel Feenstra)
* Fix curly brace check when an if statement is the alternate. (Joel Feenstra)
* Check for empty switch statements with no cases. (Matt DuVall)
* Added CONTRIBUTING.md (Nicholas C. Zakas)
* Added rule to check for missing semicolons (fixes #9) (Nicholas C. Zakas)
* Verify that file paths exist before reading the file (Matt DuVall)
* Added guard-for-in rule (fixes #1) (Nicholas C. Zakas)
* Run linting with npm test as well (Nicholas C. Zakas)
* Removed foo.txt (Nicholas C. Zakas)
* Updated config file with new no-caller ID (Nicholas C. Zakas)
* Changed name of no-arg to no-caller (Nicholas C. Zakas)
* Increased test coverage (Nicholas C. Zakas)
* Got npm test to work with istanbul, huzzah\! (Nicholas C. Zakas)
* Moved /config to /conf (Nicholas C. Zakas)
* Added script to auto-generate changelog (Nicholas C. Zakas)
* Add `quote-props` rule (Mathias Bynens)
* Cleaned up relationship between bin/eslint, lib/cli.js, and lib/eslint.js (Nicholas C. Zakas)
* Add problem count to compact formatter (Nicholas C. Zakas)
* Fix merge conflict (Nicholas C. Zakas)
* Change reporters to formatters, add format command line option. Also added tests for compact format. (Nicholas C. Zakas)
* Change reporters to formatters, add format command line option (Nicholas C. Zakas)
* Start development of 0.0.6-dev (Nicholas C. Zakas)
