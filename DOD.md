# DOD ??

**Definition of done** is: a list of criteria that has to be met before any work can be considered **done**. _Failure to meet any one of these conditions means the work is not complete_.
DoD could have different types, ex: DOD Task (Front/Back/DevOps/Doc/Design..) DOD feature, DOD Sprint, DOD release...

Below is kind of a generique DOD.

- [ ] Refactoring completed
- [ ] CI builds without errors (Also waning should be considered)
- [ ] Code run with a clean Console should (without errors)
- [ ] Any configuration or build changes documented
- [ ] Documentation updated
- [ ] Tests written and passing (X % coverage)
- [ ] Code reviewed (PR)
- [ ] Assumptions of User Story met
- [ ] Deployed to dev environment
- [ ] Feature ok-ed by UX designer
- [ ] QA performed & issues resolved
- [ ] Feature is tested against acceptance criteria (Business side)
- [ ] Feature ok-ed by Product Owner

PS: DoD can be modified, but what is important is that the initial version **must be agreed before the first Sprint**.

                               +------+
                               |      |
+----+    +----------+    +----v---+  |
|todo+--->+inProgress+--->+resolved+--+
+----+    +----------+    +-+------+
                            |
                            v
                          +-+--+
                          |done|
                          +----+

