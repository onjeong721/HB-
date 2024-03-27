# HB PAPER 디자인클론코딩 프로잭트
<img src="https://github.com/onjeong721/HBPAPER/assets/150096277/cc2bc2f4-8ed9-4bc7-9fc5-ec2542273b75" width="80%" height="auto"/>

## 프로젝트 소개
 * 사이트 주소: https://onjeong721.github.io/HBPAPER/
 * 원본 사이트: http://hbpaper.kr/
<br>

## 참여
 * 이젠 IT아카데미 강사 외 수강생
<br>

## 개발환경
<div display=flex>
  <img src="https://img.shields.io/badge/css3-1572B6?style=flat-square&logo=css3&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
  <img src="https://img.shields.io/badge/html5-E34F26?style=flat-square&logo=html5&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
  <img src="https://img.shields.io/badge/visualstudiocode-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
  <img src="https://img.shields.io/badge/adobephotoshop-31A8FF?style=flat-square&logo=adobephotoshop&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
  <img src="https://img.shields.io/badge/adobeillustrator-FF9A00?style=flat-square&logo=adobeillustrator&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
  <img src="https://img.shields.io/badge/sass-CC6699?style=flat-square&logo=sass&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
  <img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
  <img src="https://img.shields.io/badge/googledrive-4285F4?style=flat-square&logo=googledrive&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
</div>
<br>

## 기간
2023년 12월 
<br>

## 프로젝트 구조
```
강사님 pf3
 ┗ HBPAPER
 ┃ ┣ .git
 ┃ ┃ ┣ hooks
 ┃ ┃ ┃ ┣ applypatch-msg.sample
 ┃ ┃ ┃ ┣ commit-msg.sample
 ┃ ┃ ┃ ┣ fsmonitor-watchman.sample
 ┃ ┃ ┃ ┣ post-update.sample
 ┃ ┃ ┃ ┣ pre-applypatch.sample
 ┃ ┃ ┃ ┣ pre-commit.sample
 ┃ ┃ ┃ ┣ pre-merge-commit.sample
 ┃ ┃ ┃ ┣ pre-push.sample
 ┃ ┃ ┃ ┣ pre-rebase.sample
 ┃ ┃ ┃ ┣ pre-receive.sample
 ┃ ┃ ┃ ┣ prepare-commit-msg.sample
 ┃ ┃ ┃ ┣ push-to-checkout.sample
 ┃ ┃ ┃ ┣ sendemail-validate.sample
 ┃ ┃ ┃ ┗ update.sample
 ┃ ┃ ┣ info
 ┃ ┃ ┃ ┗ exclude
 ┃ ┃ ┣ logs
 ┃ ┃ ┃ ┣ refs
 ┃ ┃ ┃ ┃ ┣ heads
 ┃ ┃ ┃ ┃ ┃ ┗ main
 ┃ ┃ ┃ ┃ ┗ remotes
 ┃ ┃ ┃ ┃ ┃ ┗ origin
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ HEAD
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ main
 ┃ ┃ ┃ ┗ HEAD
 ┃ ┃ ┣ objects
 ┃ ┃ ┃ ┣ 02
 ┃ ┃ ┃ ┃ ┗ 65dbff19381df676ffd2cb69ff47e9f1e8299a
 ┃ ┃ ┃ ┣ 03
 ┃ ┃ ┃ ┃ ┗ 1f624e1fb04a3fe14de74ee2d25d7663a5697f
 ┃ ┃ ┃ ┣ 07
 ┃ ┃ ┃ ┃ ┗ eca87ec790114c30328d78761031442774ff4d
 ┃ ┃ ┃ ┣ 0f
 ┃ ┃ ┃ ┃ ┗ fa88b4ad7d2675652442f57603e88e01354e89
 ┃ ┃ ┃ ┣ 10
 ┃ ┃ ┃ ┃ ┗ 6aa6d849e1daa40f806eaefdda3911c42c64b3
 ┃ ┃ ┃ ┣ 12
 ┃ ┃ ┃ ┃ ┗ dc0a2ab138aa61f3e111dd55194b85c976a2d2
 ┃ ┃ ┃ ┣ 15
 ┃ ┃ ┃ ┃ ┗ 4279e115b3b634414674a350a593f8166c2327
 ┃ ┃ ┃ ┣ 20
 ┃ ┃ ┃ ┃ ┣ 21d4aa3138741f8d3811167dbae4f6622e2021
 ┃ ┃ ┃ ┃ ┗ bc93c4848e89d5e9eda713a1b207e2ab63ccd7
 ┃ ┃ ┃ ┣ 23
 ┃ ┃ ┃ ┃ ┗ 7585aca69ec9d147ffeebfde728ec74ba2e76f
 ┃ ┃ ┃ ┣ 24
 ┃ ┃ ┃ ┃ ┗ 8a06f483eb013b85b62f1e147bfd6284bda9dd
 ┃ ┃ ┃ ┣ 2b
 ┃ ┃ ┃ ┃ ┣ 1edb92db7221d01669c472a18949b4a70ca338
 ┃ ┃ ┃ ┃ ┗ de431c06e81ea9d9cab31e317d861af2dd3f90
 ┃ ┃ ┃ ┣ 2d
 ┃ ┃ ┃ ┃ ┗ 9577ad9170a9fe3074cb03fa2226972c23739e
 ┃ ┃ ┃ ┣ 30
 ┃ ┃ ┃ ┃ ┗ aa92d635900c4e17478c31f45dfab36ee49286
 ┃ ┃ ┃ ┣ 31
 ┃ ┃ ┃ ┃ ┗ 07b68439f003cf9b57e8cb3f65755366814a24
 ┃ ┃ ┃ ┣ 39
 ┃ ┃ ┃ ┃ ┣ 13c41a7d7db2ae7710af2c23780053b1430902
 ┃ ┃ ┃ ┃ ┣ ac3be206f8b6b994f5d1ef6c85d4e73fcba48f
 ┃ ┃ ┃ ┃ ┗ f6c898b5186c91acc1ef0817258d437a0c9dbc
 ┃ ┃ ┃ ┣ 3a
 ┃ ┃ ┃ ┃ ┗ 6f3686142e8278bc58de6c53289356f9c5d75d
 ┃ ┃ ┃ ┣ 3c
 ┃ ┃ ┃ ┃ ┗ 865e44cfa2f03cc0f6d338a7e31f7eb0fed4d3
 ┃ ┃ ┃ ┣ 42
 ┃ ┃ ┃ ┃ ┗ dd1c40077d2128b988cbe3a2448391bf1e096f
 ┃ ┃ ┃ ┣ 45
 ┃ ┃ ┃ ┃ ┗ 3729655d349af99e40ccfa65216b6ba3dff97c
 ┃ ┃ ┃ ┣ 48
 ┃ ┃ ┃ ┃ ┗ 3fb403d058e756013fd1ab2030c64a4058224c
 ┃ ┃ ┃ ┣ 4f
 ┃ ┃ ┃ ┃ ┗ 152c29d891717d79b8fe687639d5297b949c9c
 ┃ ┃ ┃ ┣ 56
 ┃ ┃ ┃ ┃ ┗ 20201f6446d6e966abd1a9d5dc85296f709a27
 ┃ ┃ ┃ ┣ 6b
 ┃ ┃ ┃ ┃ ┣ 79827e3e24a2e7b63fb6ae86cfe2849912b3ae
 ┃ ┃ ┃ ┃ ┗ c5d80cb32a46b51b0d1a2b5994693527a3253d
 ┃ ┃ ┃ ┣ 6d
 ┃ ┃ ┃ ┃ ┣ 0dca9b5939c0c0c8248a2a97277af91758fc00
 ┃ ┃ ┃ ┃ ┗ 678b6b345d1a55185967b8008eff842fde4800
 ┃ ┃ ┃ ┣ 6e
 ┃ ┃ ┃ ┃ ┗ ce2e0d69d4be17359ee2f6a485ef62fb193520
 ┃ ┃ ┃ ┣ 71
 ┃ ┃ ┃ ┃ ┗ bda96ab469ca5aa8c60ba92bb46ed3b923a13b
 ┃ ┃ ┃ ┣ 7b
 ┃ ┃ ┃ ┃ ┗ bc8e9a8ea282771fdd8a6dc3da164dd99a17f5
 ┃ ┃ ┃ ┣ 7f
 ┃ ┃ ┃ ┃ ┗ 7259c5caa24a86058b386a84a7e47ae4a48d81
 ┃ ┃ ┃ ┣ 80
 ┃ ┃ ┃ ┃ ┗ b7839774460bbba11b26619780069084e38ec4
 ┃ ┃ ┃ ┣ 81
 ┃ ┃ ┃ ┃ ┗ 172492ad58052dc532019d296554b58f84b1df
 ┃ ┃ ┃ ┣ 82
 ┃ ┃ ┃ ┃ ┗ d3e72e8840f5c870f955408d895051b464a762
 ┃ ┃ ┃ ┣ 89
 ┃ ┃ ┃ ┃ ┗ 4450d23d4d78da4aafdf7e5e5b576b2b58cccc
 ┃ ┃ ┃ ┣ 8c
 ┃ ┃ ┃ ┃ ┗ c9680b9bfe17d6031c22e188a7db5c272293b7
 ┃ ┃ ┃ ┣ 8f
 ┃ ┃ ┃ ┃ ┗ 9b7687a9673accd4c8378b649400df58d218c6
 ┃ ┃ ┃ ┣ 90
 ┃ ┃ ┃ ┃ ┗ b117dbc80a9a1c25bbaf468f6437a021be037e
 ┃ ┃ ┃ ┣ 93
 ┃ ┃ ┃ ┃ ┗ 9f785bd986dad762182a2ee8191751f06367cc
 ┃ ┃ ┃ ┣ a4
 ┃ ┃ ┃ ┃ ┗ c7ea2812a2e5ac2270d6babcf0652def2e2184
 ┃ ┃ ┃ ┣ a5
 ┃ ┃ ┃ ┃ ┗ 08d8e90a59d33bf12630ac9c976bf7325d430b
 ┃ ┃ ┃ ┣ a6
 ┃ ┃ ┃ ┃ ┗ f33799f47a49f8e64318df913ffa8abd6dc664
 ┃ ┃ ┃ ┣ b4
 ┃ ┃ ┃ ┃ ┗ ea3c57cac736ef0d8f97bf1a777b799dc1a3ef
 ┃ ┃ ┃ ┣ b7
 ┃ ┃ ┃ ┃ ┗ 24b4685dedc74a926c4817f01e5a91e4813345
 ┃ ┃ ┃ ┣ ba
 ┃ ┃ ┃ ┃ ┗ 4527a0fd6177efa5ca60f5cefde14bc4bbf907
 ┃ ┃ ┃ ┣ bd
 ┃ ┃ ┃ ┃ ┗ 1e2c92306254069b2c2f2ac00456bbd9939cb3
 ┃ ┃ ┃ ┣ c0
 ┃ ┃ ┃ ┃ ┗ f038d2ad604cc4639e2d53bf412f97ea071d00
 ┃ ┃ ┃ ┣ c5
 ┃ ┃ ┃ ┃ ┣ 70534f963c173466fc8218e8fa84b7b77752d1
 ┃ ┃ ┃ ┃ ┗ d36007cccad4bd72aff3082d5f92379df4932d
 ┃ ┃ ┃ ┣ cb
 ┃ ┃ ┃ ┃ ┗ 849407f325fd2c08a3d99346beb5fae9733300
 ┃ ┃ ┃ ┣ d0
 ┃ ┃ ┃ ┃ ┗ 3e9247dc26c59153b641a0f8b403b7d7181108
 ┃ ┃ ┃ ┣ d2
 ┃ ┃ ┃ ┃ ┗ 1ca936f99c1f9fac1a611a565708bef466e506
 ┃ ┃ ┃ ┣ d4
 ┃ ┃ ┃ ┃ ┣ 13d007f2c1d58a2034260c12925cca23846b9a
 ┃ ┃ ┃ ┃ ┗ 98564b17257c7cd98da28aee948c24f7f99ff0
 ┃ ┃ ┃ ┣ d6
 ┃ ┃ ┃ ┃ ┗ c666bdd4f49ec0ba8e8c67657839144b0661ec
 ┃ ┃ ┃ ┣ e1
 ┃ ┃ ┃ ┃ ┗ 07c733f402d86c71879db77e5b256c0bd4b729
 ┃ ┃ ┃ ┣ e2
 ┃ ┃ ┃ ┃ ┗ 1fc3df6b746970f476e3caab3784abbacb1a94
 ┃ ┃ ┃ ┣ e7
 ┃ ┃ ┃ ┃ ┗ a2ce05aabf1240f80bbaf6d7fc9b6698d0a81e
 ┃ ┃ ┃ ┣ ea
 ┃ ┃ ┃ ┃ ┗ 0cc2204128fbc45d5d7667558ff0ebf9d71871
 ┃ ┃ ┃ ┣ ee
 ┃ ┃ ┃ ┃ ┗ bcbb75ffaf07cf911c6e0f42acf03cc09c035f
 ┃ ┃ ┃ ┣ f0
 ┃ ┃ ┃ ┃ ┗ 8e989fe6935349ee45c4dbe9f87cddf4dcc856
 ┃ ┃ ┃ ┣ f1
 ┃ ┃ ┃ ┃ ┗ 0f2331e9fddcff472f53dfe4bcd5895c0fb009
 ┃ ┃ ┃ ┣ f2
 ┃ ┃ ┃ ┃ ┗ 5abf54ec5bfb590bc5f6be8fb6e6b004be3ac6
 ┃ ┃ ┃ ┣ f4
 ┃ ┃ ┃ ┃ ┗ 02dec371b0e524a523f5fb47bd9e334fd3c4d0
 ┃ ┃ ┃ ┣ f5
 ┃ ┃ ┃ ┃ ┗ 1780fb37e16be2d34d38ec267fba2f45c7dfbf
 ┃ ┃ ┃ ┣ f6
 ┃ ┃ ┃ ┃ ┗ fc030a9db1336a19cb8908ffc1598cd591abd7
 ┃ ┃ ┃ ┣ fa
 ┃ ┃ ┃ ┃ ┗ 69b29ad5e464b04c0d405fd820e71242bf9070
 ┃ ┃ ┃ ┣ fd
 ┃ ┃ ┃ ┃ ┣ 9fae3d8c895cd2b71b84d0792806e6095b784f
 ┃ ┃ ┃ ┃ ┗ d80632edf2c73c680e379f793806995470cd1c
 ┃ ┃ ┃ ┗ pack
 ┃ ┃ ┃ ┃ ┣ pack-8e3d1fe651b9aab549e3fef42924cbcee30cb413.idx
 ┃ ┃ ┃ ┃ ┣ pack-8e3d1fe651b9aab549e3fef42924cbcee30cb413.pack
 ┃ ┃ ┃ ┃ ┗ pack-8e3d1fe651b9aab549e3fef42924cbcee30cb413.rev
 ┃ ┃ ┣ refs
 ┃ ┃ ┃ ┣ heads
 ┃ ┃ ┃ ┃ ┗ main
 ┃ ┃ ┃ ┗ remotes
 ┃ ┃ ┃ ┃ ┗ origin
 ┃ ┃ ┃ ┃ ┃ ┣ HEAD
 ┃ ┃ ┃ ┃ ┃ ┗ main
 ┃ ┃ ┣ COMMIT_EDITMSG
 ┃ ┃ ┣ config
 ┃ ┃ ┣ description
 ┃ ┃ ┣ FETCH_HEAD
 ┃ ┃ ┣ HEAD
 ┃ ┃ ┣ index
 ┃ ┃ ┣ ORIG_HEAD
 ┃ ┃ ┗ packed-refs
 ┃ ┣ css
 ┃ ┃ ┣ font
 ┃ ┃ ┃ ┗ HSGyeoulNoonkott2.0-Regular.woff
 ┃ ┃ ┣ aside.css
 ┃ ┃ ┣ benefit.css
 ┃ ┃ ┣ common.css
 ┃ ┃ ┣ download.css
 ┃ ┃ ┣ font.css
 ┃ ┃ ┣ footer.css
 ┃ ┃ ┣ ham.css
 ┃ ┃ ┣ header.css
 ┃ ┃ ┣ main.css
 ┃ ┃ ┣ mission.css
 ┃ ┃ ┣ point.css
 ┃ ┃ ┣ reset.css
 ┃ ┃ ┣ response.css
 ┃ ┃ ┗ title.css
 ┃ ┣ img
 ┃ ┃ ┣ 3h.png
 ┃ ┃ ┣ accuniq.svg
 ┃ ┃ ┣ apple.png
 ┃ ┃ ┣ arrowUp.svg
 ┃ ┃ ┣ blog_btn.png
 ┃ ┃ ┣ busi_01.jpg
 ┃ ┃ ┣ busi_01.png
 ┃ ┃ ┣ busi_02.jpg
 ┃ ┃ ┣ customcenter.svg
 ┃ ┃ ┣ dash1png.png
 ┃ ┃ ┣ dash2.png
 ┃ ┃ ┣ google.png
 ┃ ┃ ┣ hd_logo_w.png
 ┃ ┃ ┣ headset.svg
 ┃ ┃ ┣ lang.png
 ┃ ┃ ┣ lang_arrow.png
 ┃ ┃ ┣ lang_arrow_w.png
 ┃ ┃ ┣ lang_w.png
 ┃ ┃ ┣ logo-lpoint-y.png
 ┃ ┃ ┣ logo.png
 ┃ ┃ ┣ logo.svg
 ┃ ┃ ┣ logotext.svg
 ┃ ┃ ┣ lotte-members.png
 ┃ ┃ ┣ message.svg
 ┃ ┃ ┣ news_01.jpg
 ┃ ┃ ┣ news_02.jpg
 ┃ ┃ ┣ news_03.jpg
 ┃ ┃ ┣ news_04.jpg
 ┃ ┃ ┣ object-bg.png
 ┃ ┃ ┣ paper_01.jpg
 ┃ ┃ ┣ paper_02.jpg
 ┃ ┃ ┣ paper_03.jpg
 ┃ ┃ ┣ paper_04.jpg
 ┃ ┃ ┣ paper_05.jpg
 ┃ ┃ ┣ paper_06.jpg
 ┃ ┃ ┣ paper_07.jpg
 ┃ ┃ ┣ qrcode.jpg
 ┃ ┃ ┣ title_01.jpg
 ┃ ┃ ┣ title_02.jpg
 ┃ ┃ ┣ title_04.jpg
 ┃ ┃ ┣ title_bg1.jpg
 ┃ ┃ ┣ uparrow.svg
 ┃ ┃ ┗ web.png
 ┃ ┣ scss
 ┃ ┃ ┗ main.scss
 ┃ ┣ index.html
 ┃ ┗ README.md
```

## 후기


