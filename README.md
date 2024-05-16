# プロジェクト名

Inspirit AI Ambassador Meeting より、5/12 日曜日の授業内容は実技でした。みんなで AI を使った検証をしました。

![GIF](resource/class_0512.gif)

## 目的

このノートブックを元に色々、検証していきます。

# 3.0 Deploying on huggingface spaces:

Once you made a Gradio demo, you can host it permanently on Hugging Spaces very easily:

Here are the steps to that (shown in the GIF below):

A. First, create a Hugging Face account if you do not already have one, by visiting https://huggingface.co/ and clicking "Sign Up"

B. Once you are logged in, click on your profile picture and then click on "New Space" underneath it to get to this page: https://huggingface.co/new-space

C. Give your Space a name and a license. Select "Gradio" as the Space SDK, and then choose "Public" if you are fine with everyone accessing your Space and the underlying code

D. Then you will find a page that provides you instructions on how to upload your files into the Git repository for that Space. You may also need to add a `requirements.txt` file to specify any Python package dependencies.

E. Once you have pushed your files, that's it! Spaces will automatically build your Gradio demo allowing you to share it with anyone, anywhere!

![GIF](https://huggingface.co/blog/assets/28_gradio-spaces/spaces-demo-finalized.gif)

## ライセンス

このプロジェクトは [MIT] のもとで公開されています。詳細は [LICENSE.md](LICENSE.md) を参照してください。

## お問い合わせ

質問やフィードバックは [meicha365@pm.me] までお願いします。