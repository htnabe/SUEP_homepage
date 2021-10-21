---
title: "アプリに関するフィードバック"
date: 2021-10-21T18:09:20+09:00
draft: false
---
{{< rawhtml >}}
<p>フィードバックの内容は直接開発者に届きます。個人情報の取り扱いについては<a href="https://suep.netlify.app/post/plivacypolicy/" target="_blank" rel=”noreferrer”>こちら</a>をご確認ください。</p>
  <form name="feedback" method="POST" netlify>
    <div class="form-item">
      <label><input type="text" name="name" placeholder="お名前 または ニックネーム" /></label>
   </div>
    <div class="form-item">
      <label><input type="email" name="email" placeholder="メールアドレス（任意）" /></label>
    </div>
    <div class="form-item">
      <label>
        <select type="subject" name="subject" >
          <option value="">フィードバックの種類として当てはまるもの</option>
          <option value="選択肢1">バグを見つけました！</option>
          <option value="選択肢2">こういう機能があると良いかも</option>
          <option value="選択肢3">使いにくい機能があります</option>
          <option value="選択肢4">その他</option>
        </select>
      </label>
      </div>
        <div class="form-item">
          <label><textarea name="message" placeholder="メッセージ"></textarea></label>
      </div>
      <div class="send-Button">
        <button type="submit">送信</button>
      </div>
    </form>
{{< /rawhtml >}}
