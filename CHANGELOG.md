# Changelog

## [v1.4.0](https://github.com/didix21/mdutils/tree/v1.4.0) (2022-05-31)

[Full Changelog](https://github.com/didix21/mdutils/compare/v1.3.1...v1.4.0)

**Implemented enhancements:**

- Add fontsize increase option for Paragraph [\#54](https://github.com/didix21/mdutils/issues/54)
- Added `get\_md\_text` method to `MdUtils` class. [\#61](https://github.com/didix21/mdutils/pull/61) ([Patitotective](https://github.com/Patitotective))

**Fixed bugs:**

- Unwanted line break in link url breaks the link [\#70](https://github.com/didix21/mdutils/issues/70)
- Varying Title level leads to IndexError in \_\_add\_new\_item\_table\_of\_content [\#68](https://github.com/didix21/mdutils/issues/68)
- GH-70, GH-73: fix unwanted link and table breaks [\#74](https://github.com/didix21/mdutils/pull/74) ([didix21](https://github.com/didix21))
- Escape "|" in Table.create\_table [\#63](https://github.com/didix21/mdutils/pull/63) ([jaredliw](https://github.com/jaredliw))

**Closed issues:**

- travis-ci.org is ceased and tests are not running [\#62](https://github.com/didix21/mdutils/issues/62)

**Merged pull requests:**

- Import coverage to codecov [\#66](https://github.com/didix21/mdutils/pull/66) ([didix21](https://github.com/didix21))
- 62: Move test workflow from travis to github actions [\#65](https://github.com/didix21/mdutils/pull/65) ([didix21](https://github.com/didix21))

## [v1.3.1](https://github.com/didix21/mdutils/tree/v1.3.1) (2021-07-09)

[Full Changelog](https://github.com/didix21/mdutils/compare/v1.3.0...v1.3.1)

**Fixed bugs:**

- NameError: name 'create\_md\_file' is not define [\#50](https://github.com/didix21/mdutils/issues/50)
- Solve max text length [\#6](https://github.com/didix21/mdutils/issues/6)
- convert value to str before adding it to a char [\#56](https://github.com/didix21/mdutils/pull/56) ([anaskhl](https://github.com/anaskhl))

**Merged pull requests:**

- Add release drafter action [\#58](https://github.com/didix21/mdutils/pull/58) ([didix21](https://github.com/didix21))
- Add PR labeler action [\#57](https://github.com/didix21/mdutils/pull/57) ([didix21](https://github.com/didix21))
- Fix \#6: add option to wrap text on new lines, paragraphs and writes [\#53](https://github.com/didix21/mdutils/pull/53) ([mhmdkanj](https://github.com/mhmdkanj))
- make text\_align be a list not only str or None [\#47](https://github.com/didix21/mdutils/pull/47) ([sgsokol](https://github.com/sgsokol))

## [v1.3.0](https://github.com/didix21/mdutils/tree/v1.3.0) (2020-09-12)

[Full Changelog](https://github.com/didix21/mdutils/compare/v1.2.2...v1.3.0)

**Implemented enhancements:**

- Implement \#43 Allow table of contents to generate from arbitrary depth of headers [\#44](https://github.com/didix21/mdutils/pull/44) ([mythWizard](https://github.com/mythWizard))

**Fixed bugs:**

- Default text align for tables should use --- [\#42](https://github.com/didix21/mdutils/issues/42)
- Fix \#42 Default table's text\_align should be '---' [\#45](https://github.com/didix21/mdutils/pull/45) ([didix21](https://github.com/didix21))

**Closed issues:**

- Allow creation of Table of Contents with arbitrary depth [\#43](https://github.com/didix21/mdutils/issues/43)
- write file to specified path  [\#41](https://github.com/didix21/mdutils/issues/41)

## [v1.2.2](https://github.com/didix21/mdutils/tree/v1.2.2) (2020-06-21)

[Full Changelog](https://github.com/didix21/mdutils/compare/v1.2.1...v1.2.2)

**Implemented enhancements:**

- Add support for markdown lists [\#4](https://github.com/didix21/mdutils/issues/4)

**Fixed bugs:**

- Missing .md extension when filename has 'md' [\#37](https://github.com/didix21/mdutils/issues/37)
- Table of contents link does not work when headers contain special characters [\#36](https://github.com/didix21/mdutils/issues/36)
- Fix \#36: Delete special characters when creating toc links [\#40](https://github.com/didix21/mdutils/pull/40) ([didix21](https://github.com/didix21))
- Fix \#37: Add .md extension if name contains md word [\#39](https://github.com/didix21/mdutils/pull/39) ([didix21](https://github.com/didix21))

**Closed issues:**

- SyntaxError: invalid syntax [\#31](https://github.com/didix21/mdutils/issues/31)

**Merged pull requests:**

- Update issue templates [\#35](https://github.com/didix21/mdutils/pull/35) ([didix21](https://github.com/didix21))
- Create CODE\_OF\_CONDUCT.md [\#34](https://github.com/didix21/mdutils/pull/34) ([didix21](https://github.com/didix21))
- update Readme.md [\#32](https://github.com/didix21/mdutils/pull/32) ([Alexmod](https://github.com/Alexmod))

## [v1.2.1](https://github.com/didix21/mdutils/tree/v1.2.1) (2020-05-08)

[Full Changelog](https://github.com/didix21/mdutils/compare/v1.1.1...v1.2.1)

**Merged pull requests:**

- Add support list in markdown [\#30](https://github.com/didix21/mdutils/pull/30) ([didix21](https://github.com/didix21))

## [v1.1.1](https://github.com/didix21/mdutils/tree/v1.1.1) (2020-04-20)

[Full Changelog](https://github.com/didix21/mdutils/compare/v1.1.0...v1.1.1)

## [v1.1.0](https://github.com/didix21/mdutils/tree/v1.1.0) (2020-04-20)

[Full Changelog](https://github.com/didix21/mdutils/compare/v1.0.0...v1.1.0)

**Implemented enhancements:**

- Inline links [\#12](https://github.com/didix21/mdutils/issues/12)
- Create an Example [\#5](https://github.com/didix21/mdutils/issues/5)
- Add support for markdown images [\#3](https://github.com/didix21/mdutils/issues/3)
- Features to develop [\#2](https://github.com/didix21/mdutils/issues/2)

**Closed issues:**

- Add HTML for image support [\#28](https://github.com/didix21/mdutils/issues/28)
- Exclude IDE related files from project [\#24](https://github.com/didix21/mdutils/issues/24)
- how [\#23](https://github.com/didix21/mdutils/issues/23)
- Write to specified path? [\#22](https://github.com/didix21/mdutils/issues/22)
- TextUtils.text\_color adds an extra space [\#20](https://github.com/didix21/mdutils/issues/20)
- Reference-Style Links [\#14](https://github.com/didix21/mdutils/issues/14)

**Merged pull requests:**

- Add HTML for image support \#28 [\#29](https://github.com/didix21/mdutils/pull/29) ([didix21](https://github.com/didix21))
- Add support for markdown images \#3 [\#27](https://github.com/didix21/mdutils/pull/27) ([didix21](https://github.com/didix21))
- Add coveralls [\#26](https://github.com/didix21/mdutils/pull/26) ([arnsangra](https://github.com/arnsangra))
- Exclude ide files [\#25](https://github.com/didix21/mdutils/pull/25) ([arnsangra](https://github.com/arnsangra))
- FIX \#20: Delete TextUtils.text\_color\(\) extra spaces [\#21](https://github.com/didix21/mdutils/pull/21) ([didix21](https://github.com/didix21))

## [v1.0.0](https://github.com/didix21/mdutils/tree/v1.0.0) (2018-05-10)

[Full Changelog](https://github.com/didix21/mdutils/compare/b1ce055fdb9c07ca0f4c8e748be0321dcc996937...v1.0.0)

**Implemented enhancements:**

- Improve new\_header giving the option of not to include a header in the table of contents. [\#11](https://github.com/didix21/mdutils/issues/11)
- New method to add code [\#10](https://github.com/didix21/mdutils/issues/10)
- Improve write method: give format to text and place it with markers [\#9](https://github.com/didix21/mdutils/issues/9)

**Fixed bugs:**

- when add text as inline code with color doesn't work. [\#8](https://github.com/didix21/mdutils/issues/8)
- Solve line break on new\_line method [\#7](https://github.com/didix21/mdutils/issues/7)

**Merged pull requests:**

- Development [\#1](https://github.com/didix21/mdutils/pull/1) ([didix21](https://github.com/didix21))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
