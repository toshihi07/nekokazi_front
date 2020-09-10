<template>
  <div class="footer">
    <div class="container">
      <div class="footer_above">
        <div class="footer_above_twitter_area">
          <div class="d-flex">
            <figure claas="twitter_account_thum">
              <img
                src="https://pbs.twimg.com/profile_images/1133359984467619841/_0jhqQjf_bigger.jpg"
                alt=""
              />
            </figure>
            <div class="twitter_account_name_area">
              <div class="twitter_account_name_area_name">
                猫遊技場(ネコカジ)新宿
              </div>
              <div class="twitter_account_name_area_id">@neko_kaji</div>
            </div>
          </div>
          <div class="footer_twitter_tweet">
            明日8日(火)18:30〜 ✨AJPC公式予選【3枠保証】✨ を開催します❣️
            ♡参加費3,500円 ♡12,500点スタート ♡リバイorアドオン1,500円
            ♧上位3名の方に 【AJPC Day1参加チケット】 を進呈しますbr❣️
            詳細➡️http://pokerguild.jp/tourneys/95199
          </div>
          <figure class="twitter_img_area">
            <img src="" alt="" />
          </figure>
          <div class="footer_twitter_footer">
            <div>埋め込む</div>
            <div>twitterで表示</div>
          </div>
        </div>
        <div class="footer_above_access_area">
          <div class="footer_above_access_area_title">猫遊技場 -ネコカジ-</div>
          <p class="footer_above_access_area_position">
            東京都新宿区歌舞伎町1-22-9 Jゴールドビル6F TEL：03-6228-0366
            営業時間：平日 17:00-23:30／土日祝 15:00-23:30
            アクセス：JR新宿駅より徒歩４分
          </p>
          <div class="footer_above_sns_area">
            <div>facebook_icon</div>
            <div>twitter_icon</div>
          </div>
        </div>
        <div class="footer_above_contact_area">
          <router-link to=""
            ><div class="footer_above_contact_btn">
              <p class="footer_above_contact_btn_upper">お問い合わせ</p>
              <p class="footer_above_contact_btn_lower">求人情報はこちらから</p>
            </div></router-link
          >
        </div>
      </div>
      <div class="footer_copyright_area">
        <p>Copyright © 猫遊戯場-ネコカジ All Rights Reserved.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
  props: {
    title: {
      type: String,
      default: ""
    }
  }
};
</script>

<style lang="css" scoped>
.footer {
  background: #f5f5f5;
}

.footer_above {
  display: flex;
  justify-content: flex-start;
  padding-bottom: 50px;
  border-bottom: 1px solid #e5e5e5;
  padding: 2rem 0;
}

.footer_copyright_area {
  padding: 50px 0;
  text-align: center;
}

.footer_above {
  display: flex;
}

.footer_above_twitter_area,
.footer_above_access_area,
.footer_above_contact_area {
  flex: 1;
  padding: 0 10px;
}

.footer_above_twitter_area {
  background: white;
}

.twitter_account_name_area {
  padding-left: 10px;
}

.twitter_account_name_area_name {
  margin-top: 15px;
}

.twitter_account_name_area_id {
  margin-top: 10px;
}

.footer_twitter_tweet {
  margin: 10px 0;
}

.footer_twitter_footer {
  display: flex;
  justify-content: space-between;
  padding-bottom: 10px;
}

.footer_above_access_area_title {
  font-size: larger;
  font-weight: bold;
  padding-bottom: 15px;
  border-bottom: 1px solid #337ab7;
  margin-bottom: 20px;
}

.footer_above_access_area_position {
  line-height: 1.5rem;
}

.footer_above_sns_area {
  display: flex;
  margin-top: 10px;
}

.footer_above_contact_btn {
  background-color: #919ac2;
  padding: 20px;
  border-radius: 5px;
  border: 2px solid #043c78;
}

.footer_above_contact_btn_upper {
  text-align: center;
  color: white;
  font-size: 1.443em;
}

.footer_above_contact_btn_lower {
  margin-top: 5px;
  text-align: center;
}
</style>
