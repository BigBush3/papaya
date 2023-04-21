<template>
  <div
    style="
      overflow: hidden;
      overflow-y: hidden; /*для вертикального*/
      overflow-x: hidden; /*для горизонтального*/
      
    "
  >
    <div style="margin-left: 42%; object-fit: fill; width: 80%">
      <img
        class="img-fluid"
        style="height: auto; position: fixed; max-width: 160%;"
        src="../../accets/Images/Papaya.png"
      />
    </div>

    <div>
      <div
        style="
          display: flex;
          justify-content: center;
          margin-right: 85%;
          margin-top: 9%;
        "
      >
        <div style="display: flex; width: 30%">
          <div class="data-title" style="display: flex">
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
      </div>

      <div style="width: 1%; margin-left: 6%;max-width: 300px;">
        <p
          class=""
          style="
            font-style: normal;
            font-weight: 400;
            font-size: 24px;
            line-height: 28px;
            /* identical to box height */

            letter-spacing: 0.15em;
            margin-left: 5%;
            color: #1d2024;
          "
        >
          Translation Exchange
        </p>
      </div>
      <div style="width: 18%;margin-left: 5%; margin-top: 3%">
        <p
          style="
            font-style: normal;
            font-weight: 300;
            font-size: 16px;
            line-height: 150%;
            /* or 24px */

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
        <div style="margin-left: 5%; margin-top: 3%">
          <AccountLogin />
        </div>
        <div style="margin-left: 5%; margin-top: 1%">
          <RegForm />
        </div>
        <div></div>
        <footer>
          <div style="margin-left: 5%; margin-top: 10%;width: 60%;">
            <p
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
          <div style="margin-left: 5%; margin-top: 1%;width: 40%;">
            <p>
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

<style></style>
