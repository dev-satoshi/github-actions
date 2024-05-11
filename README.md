# GitHub Actions Sandbox

## 目次
<!-- 番号付きのリスト -->
1. [hello_world](#hello_world)
2. [check_bats_version](#check_bats_version)
3. [add_issue_to_project](#add_issue_to_project)
4. [add_to_project](#add_to_project)


<h2 id="hello_world">hello_world</h2>
hello_worldを出力するWorkflow

[View the code](https://github.com/dev-satoshi/github-actions-practice/blob/main/.github/workflows/hello_world.yml)


<h2 id="check_bats_version">check_bats_version</h2>
batsのversionを表示するWorkflow

[View the code](https://github.com/dev-satoshi/github-actions-practice/blob/main/.github/workflows/check_bats_version.yml)


<h2 id="add_issue_to_project">add_issue_to_project</h2>
Issue作成時に指定したProjectに自動追加するWorkflow

<details>
<summary>Memo</summary>
  
- labeld(オプション)を使うことで、特定のラベルがついたIssueだけをProjectに追加することもできる<br>
- label-operator(オプション)で、ラベルフィルタの動作を指定する
</details>

[View the code](https://github.com/dev-satoshi/github-actions-practice/blob/main/.github/workflows/add_issue_to_project.yml)


<h2 id="add_to_project">add_to_project</h2>
IssueまたはPull Request作成時に指定したProjectに自動追加するWorkflow

[View the code](https://github.com/dev-satoshi/github-actions-practice/blob/main/.github/workflows/add_to_project.yml)
