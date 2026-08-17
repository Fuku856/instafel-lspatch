# instafel-lspatch
InstafelにLSPatchのjarを適用したものです。 <br>
[InstaEclipse](https://github.com/ReSo7200/InstaEclipse) をLSPatchマネージャーでスコープ管理し、Obtaniumで自動更新できるようにするために作成しました。 <br> <br>
GitHub Actionsのワークフローにより自動的にビルドされます。 <br>

## Base APKの入手元
GitHubのリリースからInstafelのAPK配布が無くなったため、公式サイトから取得するようにしました。 <br>
https://instafel.mamii.dev/releases/list <br>
Workflowが公式APIを直接叩いて最新版を検出し、Clone版 (`instafel_c_`) をCDNからダウンロードして、MD5を照合してからパッチを当てます。 <br>
1日2回 (日本時間 午前4時 / 午後4時) にチェックされます。 <br>

## Special Thanks
This repository is forked from YuzuMikan404's instafel-lspatch. <br>
https://github.com/YuzuMikan404/instafel-lspatch <br>

## License
This project is licensed under the Apache License 2.0, same as the original repository. See [LICENSE](LICENSE) for details. <br>
