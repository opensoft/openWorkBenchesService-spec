# openWorkBenchesService-spec

The **spec leg** of the `openworkbenchesservice` project: requirements, decisions and
acceptance criteria. The implementation lives in
[`opensoft/openWorkBenchesService-code`](https://github.com/opensoft/openWorkBenchesService-code).

**Clone the assembly root, not this repository.** This leg is mounted as a
submodule at `spec/` inside
[`opensoft/openWorkBenchesService`](https://github.com/opensoft/openWorkBenchesService), which
is what pins the commit of this repository that the project currently is:

```sh
git clone --recurse-submodules https://github.com/opensoft/openWorkBenchesService.git
cd openWorkBenchesService
make bootstrap
```

Working here directly is fine — it is an ordinary repository with an ordinary
branch. What advancing this leg does NOT do is advance the project: that is a
commit in the assembly root moving the gitlink, `contracts/spec-pin.yaml` and
any workflow `@<sha>` reference together.

Being the spec leg confers no authority over specifications. The split is
navigation; authority travels in grants, and a project that keeps spec and
code in one repository is reviewed identically.

Topic: `xf-project-openworkbenchesservice`.
