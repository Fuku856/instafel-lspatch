# instafel-lspatch
Instafelにlspatchのjar当てたやつ <br>
InstaEclipseをLSPatchマネージャーでスコープできるように、そしてObtaniumで自動更新できるように作りました。 <br>
https://github.com/ReSo7200/InstaEclipse <br>
自分用なので悪しからず。 <br>
Workflowで自動的にビルドされます。 <br>

## ベースAPKの入手元
GitHubのリリースからInstafelのAPK配布が無くなったため、公式サイトから取得するようにしました。 <br>
https://instafel.mamii.dev/releases/list <br>
Workflowが公式APIを直接叩いて最新版を検出し、Clone版 (`instafel_c_`) をCDNからダウンロードして、MD5を照合してからパッチを当てます。 <br>
1日2回 (日本時間 午前4時 / 午後4時) にチェックされます。 <br>
