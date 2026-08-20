<div align="center">

  <h2 align="center">My Open Source Contributions</h2>

  <p align="center">
    This readme includes all of my PRs merged (and issues opened) in various open source projects.
    <br />
    <a href="https://github.com/cs3org">CERN (CS3)</a>
    ·
    <a href="https://github.com/kgateway-dev/kgateway">CNCF kgateway</a>
    ·
    <a href="https://github.com/argoproj/argo-cd/">CNCF Argo CD</a>
    ·
    <a href="https://github.com/kubeedge/">CNCF KubeEdge</a>
    ·
    <a href="https://github.com/kyverno/">CNCF Kyverno</a>
    ·
    <a href="https://github.com/oras-project/">CNCF ORAS</a>
    ·
    <a href="https://github.com/kubernetes/">Kubernetes</a>
  </p>
</div>

<br>
<br>

### Total PRs merged - 79

### CERN (CS3)

**cs3org/charts**

1. [revad: update chart for reva v3.12.2 (chart 2.0.0)](https://github.com/cs3org/charts/pull/59)

**cs3org/reva-configs**

2. [ocm: warn that the /var/tmp state files are ephemeral for containers](https://github.com/cs3org/reva-configs/pull/10)
3. [Fix OCM-API link in README: githunb.com -> github.com](https://github.com/cs3org/reva-configs/pull/9)
4. [ocm: add webapp_endpoint so the example starts on reva >= v3.12](https://github.com/cs3org/reva-configs/pull/7)

**Issues opened**

1. [revad chart is pinned to v1.24.0 and fails with current reva images](https://github.com/cs3org/charts/issues/58)
2. [OCM client "insecure" flag has three different config key names across services](https://github.com/cs3org/reva-configs/issues/8)
3. [ocm/ example: the /var/tmp state files silently lose all federation state in containers](https://github.com/cs3org/reva-configs/issues/6)
4. [the ocm/ example manifests fails to start on revad: "webapp_endpoint is a required field"](https://github.com/cs3org/reva-configs/issues/5)

### CNCF kgateway

**kgateway-dev/kgateway**

1. [Introduce shared base gateway and migrate tests to go http assertions for faster tests](https://github.com/kgateway-dev/kgateway/pull/13515)
2. [Faster E2E tests for `Extauth` pkg - use native go instead of curl pod to create http reqs](https://github.com/kgateway-dev/kgateway/pull/13323)
3. [Introducing `TestInstallation.AssertionsT` method that provides a better scoped assertions provider](https://github.com/kgateway-dev/kgateway/pull/13324)
4. [Faster E2E tests for `ExtProc` pkg - use native go instead of curl pod to create http reqs](https://github.com/kgateway-dev/kgateway/pull/13446)
5. [Move `global/local rate limits`, `policyselector`, `cors`, `compression`, `backendconfigpolicy`, `csrf`, `autohostrewrite` tests from curl pods assertions to native go](https://github.com/kgateway-dev/kgateway/pull/13570)
6. [move from curl pod with native Go code for - `AttachedRoutes`, `DirectResponse`, `PathMatching`, `TimeoutRetry`, `RBAC`, `APIKeyAuth`, `JWT`, `BasicAuth`](https://github.com/kgateway-dev/kgateway/pull/13589)
7. [(chore): add migrate ZeroDowntime tests to SetupBaseGateway and go assertions](https://github.com/kgateway-dev/kgateway/pull/13597)
8. [move from curl pod with native Go code for TLS Tests](https://github.com/kgateway-dev/kgateway/pull/13840)
9. [fix: clear SetupBaseConfig after the test runs](https://github.com/kgateway-dev/kgateway/pull/13844)
10. [(chore): added yamlfmt formater + lint check in ci and make REFRESH_GOLDEN files pass lint + add EOF newline](https://github.com/kgateway-dev/kgateway/pull/13924)

**kgateway-dev/kgateway.dev**

11. [Fixed the issues I found in the docs](https://github.com/kgateway-dev/kgateway.dev/pull/669)

**kgateway-dev/community**

12. [add 1shubham7 to org member](https://github.com/kgateway-dev/community/pull/151)

### CNCF KubeEdge

**kubeedge/kubeedge**

1. [[Integration Test] - Fixing "Add a device with Twin attributes" Integration Test with query optimization and correct tests](https://github.com/kubeedge/kubeedge/pull/6136)
2. [E2E Tests for Device Plugins (deploy and register)](https://github.com/kubeedge/kubeedge/pull/6094)
3. [Moving from standard lib to `stretchr/testify`](https://github.com/kubeedge/kubeedge/pull/5837)
4. [E2E test for application with liveness probe](https://github.com/kubeedge/kubeedge/pull/5741)
5. [Test coverage for `cloud/cmd`](https://github.com/kubeedge/kubeedge/pull/5827)
6. [misspell in `schedule.yml`](https://github.com/kubeedge/kubeedge/pull/5814)
7. [Tests for `cloud/pkg/admissioncontroller` package](https://github.com/kubeedge/kubeedge/pull/5813)
8. [`Typed` tests](https://github.com/kubeedge/kubeedge/pull/5812)
9. [Added tests for `overridemanager` package](https://github.com/kubeedge/kubeedge/pull/5810)
10. [UTs for `commmandoverrider.go`](https://github.com/kubeedge/kubeedge/pull/5809)
11. [Test coverage for `cloud/pkg/dynamiccontroller` module](https://github.com/kubeedge/kubeedge/pull/5803)
12. [Added tests for `cloud/pkg/csidriver` pkg](https://github.com/kubeedge/kubeedge/pull/5795)
13. [Test coverage for `edge/pkg/metamanager/client` module - lease and node files](https://github.com/kubeedge/kubeedge/pull/5780)
14. [Added tests for pkgs in `kubernetes` module](https://github.com/kubeedge/kubeedge/pull/5778)
15. [Tests for `storage/v1` module](https://github.com/kubeedge/kubeedge/pull/5763)
16. [UT coverage for the `cloud/pkg/taskmanager/util` module](https://github.com/kubeedge/kubeedge/pull/5751)
17. [Small misspell](https://github.com/kubeedge/kubeedge/pull/5742)
18. [Test coverage for `cloud/cmd/admission` module](https://github.com/kubeedge/kubeedge/pull/5723)
19. [Test Coverage for `debug` package](https://github.com/kubeedge/kubeedge/pull/5708)
20. [Added tests for `keadm/cmd/keadm/app/cmd/debug/check.go`](https://github.com/kubeedge/kubeedge/pull/5700)
21. [Added tests for `keadm beta` and `cloud` packages](https://github.com/kubeedge/kubeedge/pull/5695)
22. [Test coverage for `keadm/cmd/keadm/app/cmd/ctl` module](https://github.com/kubeedge/kubeedge/pull/5693)
23. [Added test coverage for `pkg/stream` package](https://github.com/kubeedge/kubeedge/pull/5690)
24. [Unit tests for `cloud/pkg/cloudhub/common/helper.go`](https://github.com/kubeedge/kubeedge/pull/5687)
25. [Test coverage for `cloudstream` package](https://github.com/kubeedge/kubeedge/pull/5684)
26. [Added test coverage for `cloudstream.go`](https://github.com/kubeedge/kubeedge/pull/5682)
27. [Test coverage for `application.go`](https://github.com/kubeedge/kubeedge/pull/5675)
28. [Test coverage for `edge/pkg/metamanager/client` module - CSR and CM files](https://github.com/kubeedge/kubeedge/pull/5757)
29. [Test coverage for `edge/pkg/metamanager/client` module - pod, podstatus and secret files](https://github.com/kubeedge/kubeedge/pull/5905)
30. [CSI Driver `versionFlag` is inconsistent during CI tests](https://github.com/kubeedge/kubeedge/pull/5928)
31. [UT coverage for `cloud/pkg/devicecontroller/controller` pkg](https://github.com/kubeedge/kubeedge/pull/5970)
32. [Complete tests for `edge/pkg/metamanager/client`](https://github.com/kubeedge/kubeedge/pull/5926)
33. [tests for `edge/pkg/eventbus/mqtt/handler.go`](https://github.com/kubeedge/kubeedge/pull/6021)

**kubeedge/website**

34. [New Blog for Release KubeEdge v1.10](https://github.com/kubeedge/website/pull/535)
35. [New Blog for Release KubeEdge v1.11](https://github.com/kubeedge/website/pull/538)
36. [New Blog for Release KubeEdge v1.12](https://github.com/kubeedge/website/pull/539)
37. [New Blog for Release KubeEdge v1.13](https://github.com/kubeedge/website/pull/542)
38. [New Blog for Release KubeEdge v1.14](https://github.com/kubeedge/website/pull/541)
39. [New Blog for Release KubeEdge v1.15](https://github.com/kubeedge/website/pull/579)
40. [New Blog for Release KubeEdge v1.17](https://github.com/kubeedge/website/pull/534)
41. [Bug: We need to fix some links for local development](https://github.com/kubeedge/website/pull/567)
42. [Docs: Improving the install with `keadm` documentation](https://github.com/kubeedge/website/pull/544)
43. [Replacing Twitter with X](https://github.com/kubeedge/website/pull/543)
44. [PR template goes inside `.github` directory](https://github.com/kubeedge/website/pull/537)
45. [Case study for Cloud Native EdgeComputing Satellite (ENG)](https://github.com/kubeedge/website/pull/655)
46. [Case study for ZCITC Streamlining Urban Parking with KubeEdge](https://github.com/kubeedge/website/pull/659)

### CNCF Argo CD

**argoproj/argo-cd**

1. [docs: Update Linux host IP detection in Toolchain guide - to avoid hardcoded `eth0`](https://github.com/argoproj/argo-cd/pull/25800)
2. [fix: update Jsonnet field tag to avoid `jsonnet: {}` in manifests](https://github.com/argoproj/argo-cd/pull/25625)

### CNCF Kyverno

**kyverno/kyverno**

1. [Bug: Enabling many-to-one comparisons for `AnyNotIn` operator](https://github.com/kyverno/kyverno/pull/9462)
2. [Bug: making `images` variable consistent with the `image` variable](https://github.com/kyverno/kyverno/pull/9147)
3. [adding myself (Shubham Singh) to CONTRIBUTORS.md](https://github.com/kyverno/kyverno/pull/10149)

**kyverno/website**

4. [Value for reference variable should be fixed.](https://github.com/kyverno/website/pull/1176)
5. [Enhancement: documenting the `images` variables, `reference` and `referenceWithTag`](https://github.com/kyverno/website/pull/1162)
6. [Enhancement: added fuzzing and 3rd party security audit links to the Security section](https://github.com/kyverno/website/pull/1111)
7. [Fixed a grammatical mistake](https://github.com/kyverno/website/pull/1108)
8. [Feat: Added a new section about Admission Controllers](https://github.com/kyverno/website/pull/1086)
9. [Updated settings 'userServerSideApply' to 'useServerSideApply'](https://github.com/kyverno/website/pull/1085)

### CNCF ORAS

**oras-project/oras**

1. [chore: improving error log for `oras push` and `oras attach` when the annotation file is invalid](https://github.com/oras-project/oras/pull/1026)

**oras-project/oras-www**

2. [adding `oras manifest fetch` to the docs "Pushing_and_pulling"](https://github.com/oras-project/oras-www/pull/241)
3. [Docs: resolves markdown error and misspells in "pushing and pulling artifacts" section](https://github.com/oras-project/oras-www/pull/230)
4. [Docs: Added the Licenses badge and small "Contribution" section to readme](https://github.com/oras-project/oras-www/pull/214)

### Kubernetes

**kubernetes/website**

1. [Fix grammar in "Autoscaling Workloads" page](https://github.com/kubernetes/website/pull/49935)

### CNCF

**cncf/mentoring**

1. [Fix formatting of kpt link](https://github.com/cncf/mentoring/pull/1750)
