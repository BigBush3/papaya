<template>
  <div
    class="main"
    style="
      overflow: hidden;
      overflow-y: hidden; /*для вертикального*/
      overflow-x: hidden; /*для горизонтального*/
    "
  >
    <div style="margin-left: 44%; object-fit: fill; width: 80%">
      <img
        class="img-fluid"
        style="height: auto; position: fixed; max-width: 160%"
        src="../../accets/Images/Papaya.png"
      />
    </div>

    <div>
      
      <div
        class="aaa"
        style="
          display: flex;
          width: 30%;
          display: flex;
          justify-content: center;
         
          margin-top: 9%;
        "
      >
        <div class="data-title" style="display: flex;margin-right: 10%;" >
          <h1
            class="display-1"
            style="
              font-style: normal;
              font-weight: 500;

              line-height: 110px;
            "
          >
            Papaya
          </h1>
          <p
            class="rtext"
            style="
              font-style: normal;
              font-weight: 500;
              font-size: 30px;
              line-height: 110px;

              color: #1d2024;
            "
          >
            ®
          </p>
        </div>
      </div>

      <div style="width: 50%; z-index: 4; padding-left: 3%">
        <p
          class="trans"
          style="
            font-style: normal;
            font-weight: 400;
            font-size: 24px;
            line-height: 28px;
            /* identical to box height */

            letter-spacing: 0.15em;
            margin-left: 5%;
            color: #1d2024;
            z-index: 4;
          "
        >
          Translation Exchange
        </p>
      </div>
      <div
        class="text"
        style="
          width: 23%;
          margin-left: 5%;
          margin-top: 3%;
          z-index: 2;
          max-width: 100%;
        "
      >
        <p
          class="prt"
          style="
            font-style: normal;
            font-weight: 300;
            font-size: 16px;
            line-height: 150%;
            /* or 24px */
            z-index: ;

            color: #38484f;
          "
        >
          Translation project “Papaya” is a translation exchange marketplace, in
          which clients place orders, and translation companies/freelancers take
          orders for translation of texts of different levels of complexity from
          various sectors of the economy.
        </p>
      </div>
      <div>
        <div class="bt1" style="margin-left: 5%; margin-top: 3%">
          <AccountLogin />
        </div>
        <div class="bt2" style="margin-left: 5%; margin-top: 1%">
          <RegForm />
        </div>
        <div></div>
        <footer>
          <div class="" style="margin-left: 5%; margin-top: 10%; width: 60%">
            <p
              class="dev1"
              style="
                font-style: normal;
                font-weight: 300;
                font-size: 14px;
                line-height: 16px;
                /* identical to box height */

                color: #1d2024;
              "
            >
              Copyright © 2022 Vialtech, Inc. All rights reserved.
            </p>
          </div>
          <div style="margin-left: 5%; margin-top: 1%; width: 40%">
            <p class="dev2">
              Terms of Use | Privacy Policy | FAQs | Contact Us | Cookie
              Settings
            </p>
          </div>
          <div style="margin-left: 5%; margin-top: 1%; width: 45%">
            <p
              style="
                font-style: normal;
                font-weight: 300;
                font-size: 12px;
                line-height: 150%;
              "
            >
              Unless otherwise specified, all product and service names
              appearing in this Internet site are trademarks owned by or
              licensed to Vialtech Inc., its subsidiaries or affiliates. No use
              of any Vialtech trademark, trade name, or trade dress in this site
              may be made without the prior written authorization of Vialtech,
              except to identify the product or services of the company.
            </p>
          </div>
        </footer>
      </div>
    </div>
  </div>
</template>

<script>
import RegForm from "../Regestration/RegForm.vue";
import AccountLogin from "../Login/AccountLogin.vue";
export default {
  components: {
    RegForm,
    AccountLogin,
  },
  data() {
    return {
      isActive: false,
    };
  },
  methods: {
    open() {
      this.isActive = true;
    },
    close() {
      this.isActive = false;
    },
  },
};
</script>

<style>

@media screen and (max-width: 340px) {
  .prt {
    font-size: 14px;
    width: 218px;
  }
  .img-fluid {
    width: 565px;
  }
  .bt1 {
    width: 824px;
  }
  .bt2 {
    width: 824px;
  }
  .dev1 {
    font-size: 12px;
  }
  .dev2 {
    font-size: 12px;
  }
  .dev3 {
    font-size: 10px;
  }
  
  .rtext {
    font-size: 12px;
  }
  .aaa{
    margin-right:3%;
  }
  .display-1{
    font-size: 20px;
  }
}








@media screen and (max-width: 375px) {
  .prt {
    font-size: 14px;
    width: 218px;
  }
  .img-fluid {
    width: 565px;
  }
  .bt1 {
    width: 824px;
  }
  .bt2 {
    width: 824px;
  }
  .dev1 {
    font-size: 12px;
  }
  .dev2 {
    font-size: 12px;
  }
  .dev3 {
    font-size: 10px;
  }
  
  .rtext {
    font-size: 12px;
  }
  .aaa{
    margin-left: 10%;
  }
  
}

@media screen and (max-width: 575px) {
  .prt {
    font-size: 14px;
    width: 218px;
  }
  .img-fluid {
    width: 570px;
  }
  .bt1 {
    width: 824px;
  }
  .bt2 {
    width: 824px;
  }
  .dev1 {
    font-size: 12px;
  }
  .dev2 {
    font-size: 12px;
  }
  .dev3 {
    font-size: 10px;
  }.aaa{
    margin-left: 10%;
  }
  
}

@media screen and (max-width: 775px) {
  .prt {
    font-size: 14px;
    width: 218px;
  }
  .img-fluid {
    width: 570px;
  }
  .bt1 {
    width: 824px;
  }
  .bt2 {
    width: 824px;
  }
  .dev1 {
    font-size: 12px;
  }
  .dev2 {
    font-size: 12px;
  }
  .dev3 {
    font-size: 10px;
  }.aaa{
    margin-left: 8%;
  }
 
}
@media screen and (max-width: 800px) {
  .prt {
    font-size: 12px;
    width: 371px;
  }
  .img-fluid {
    width: 570px;
  }
  .bt1 {
    width: 824px;
  }
  .bt2 {
    width: 824px;
  }
  .dev1 {
    font-size: 12px;
  }
  .dev2 {
    font-size: 12px;
  }
  .dev3 {
    font-size: 10px;
  }
  .display-1 {
    font-size: 46px;
  }
  .rtext {
    font-size: 12px;
  }
  .trans {
  }.aaa{
    margin-left: 8%;
  }
}
@media screen and (max-width: 1024px) {
  .prt {
    width: 218px;
  }
  .img-fluid {
    width: 700px;
  }
  .bt1 {
    width: 824px;
  }
  .bt2 {
    width: 824px;
  }
  .dev1 {
    font-size: 12px;
  }
  .dev2 {
    font-size: 12px;
  }
  .dev3 {
    font-size: 10px;
  }
  .display-1 {
    font-size: 46px;
  }
  .rtext {
    font-size: 12px;
  }
  .trans {
  }.aaa{
    margin-left: 8%;
  }
}





@media screen and (max-width: 1400px) {
  .prt {
    width: 218px;
  }
  .img-fluid {
    width: 700px;
  }
  .bt1 {
    width: 824px;
  }
  .bt2 {
    width: 824px;
  }
  .dev1 {
    font-size: 12px;
  }
  .dev2 {
    font-size: 12px;
  }
  .dev3 {
    font-size: 10px;
  }
  .display-1 {
    font-size: 46px;
  }
  .rtext {
    font-size: 12px;
  }
  .trans {
  }.aaa{
    margin-left: 8%;
  }
}






</style>
