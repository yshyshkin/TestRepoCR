**Functional Review**
- [ ] [(?)][1_1] functionality works as described in the issue description
- [ ] [(?)][1_2] functionality affected by code changes identified and tested
- [ ] [(?)][1_3] manual check in complete prod environment passed `#feature` `#ticket`

**Architectural Review**
- [ ] [(?)][2_1] used architectural best practices (SOLID, KISS, DRY, GRASP, YAGNI)
- [ ] [(?)][2_2] solution doesn't introduce an another way of implementation of same things
- [ ] [(?)][2_3] controversial decisions were discussed and approved
- [ ] [(?)][2_4] solution extendability points are defined `#feature` `#ticket`

**Implementation Review**
- [ ] [(?)][3_1] branch name matches requirements, pull request has correct title
- [ ] [(?)][3_2] latest base branch was merged to target branch
- [ ] [(?)][3_3] no code defects
- [ ] [(?)][3_4] no security vulnerabilities
- [ ] [(?)][3_5] no memory leaks, no queries to storage with big result set
- [ ] [(?)][3_6] no performance issues both at code and storage levels
- [ ] [(?)][3_7] boundary values were checked
- [ ] [(?)][3_8] compatibility with minimum system requirements
- [ ] [(?)][3_9] code style consistency
- [ ] [(?)][3_10] code readability
- [ ] [(?)][3_11] no BC breaks / required BC breaks were approved
- [ ] [(?)][3_12] implementation does not break component and bundle dependencies
- [ ] [(?)][3_13] outdated functionality was marked as deprecated
- [ ] [(?)][3_14] all DI services that can be private were marked as private
- [ ] [(?)][3_15] docblocks for classes and methods were defined

**Automated Tests**
- [ ] [(?)][4_1] unit tests check functionality on class level
- [ ] [(?)][4_2] functional tests check functionality on application level
- [ ] [(?)][4_3] functional tests cover most common and negative use cases
- [ ] [(?)][4_4] implemented functionality fully covered by unit or functional tests
- [ ] [(?)][4_5] behat test scenarios were written and implemented `#feature`

**Documentation**
- [ ] [(?)][5_1] BC breaks, deprecations and upgrade instructions were added to UPGRADE*.md file
- [ ] [(?)][5_2] developers documentation in bundle was added `#feature` `#ticket`
- [ ] [(?)][5_3] solution extendability points are documented `#feature` `#ticket`
- [ ] [(?)][5_4] email about important updates was sent to developers team `#feature` `#ticket`
- [ ] [(?)][5_5] user documentation code examples were updated `#feature` `#ticket`
- [ ] [(?)][5_6] user documentation task for tech writer was created `#feature`

[1_1]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Functionalityworksasdescribedintheissuedescription
[1_2]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Functionalityaffectedbycodechangesidentifiedandtested
[1_3]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Manualcheckincompleteprodenvironmentpassed
[2_1]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Usedarchitecturalbestpractices(SOLID,KISS,DRY,GRASP,YAGNI)
[2_2]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Solutiondoesn'tintroduceananotherwayofimplementationofsamethings
[2_3]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Controversialdecisionswerediscussedandapproved
[2_4]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Solutionextendabilitypointsaredefined
[3_1]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Branchnamematchesrequirements,pullrequesthascorrecttitle
[3_2]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Latestbasebranchwasmergedtotargetbranch
[3_3]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Nocodedefects
[3_4]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Nosecurityvulnerabilities
[3_5]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Nomemoryleaks,noqueriestostoragewithbigresultset
[3_6]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Noperformanceissuesbothatcodeandstoragelevels
[3_7]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Boundaryvalueswerechecked
[3_8]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Compatibilitywithminimumsystemrequirements
[3_9]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Codestyleconsistency
[3_10]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Codereadability
[3_11]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-NoBCbreaks/requiredBCbreakswereapproved
[3_12]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Implementationdoesnotbreakcomponentandbundledependencies
[3_13]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Outdatedfunctionalitywasmarkedasdeprecated
[3_14]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-AllDIservicesthatcanbeprivateweremarkedasprivate
[3_15]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Docblocksforclassesandmethodsweredefined
[4_1]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Unittestscheckfunctionalityonclasslevel
[4_2]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Functionaltestscheckfunctionalityonapplicationlevel
[4_3]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Functionaltestscovermostcommonandnegativeusecases
[4_4]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Implementedfunctionalityfullycoveredbyunitorfunctionaltests
[4_5]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Behattestscenarioswerewrittenandimplemented
[5_1]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-BCbreaks,deprecationsandupgradeinstructionswereaddedtoUPGRADE*.mdfile
[5_2]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Developersdocumentationinbundlewasadded
[5_3]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Solutionextendabilitypointsaredocumented
[5_4]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Emailaboutimportantupdateswassenttodevelopersteam
[5_5]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Userdocumentationcodeexampleswereupdated
[5_6]: https://magecore.atlassian.net/wiki/display/ORODEV/Code+Review+Checklist#CodeReviewChecklist-Userdocumentationtaskfortechwriterwascreated
