<template>
  <!-- Кнопка-триггер модального окна -->
  <div
    class="modal fade"
    id="exampleModalToggle"
    aria-hidden="true"
    aria-labelledby="exampleModalToggleLabel"
    tabindex="-1"
  >
    <div class="modal-xl">
      <div class="modal-dialog modal-lg">
        <div
          style="height: 100%; border-radius: 67px; flex-wrap: wrap"
          class="modal-content"
        >
          <div class="modal-header">
            <h5
              style="font-size: 18px; margin-left: 5%; margin-top: 3%    
            ;  font-style: normal;
              font-weight: 400;
              
              line-height: 120%;"
              class="modal-title"
              id="exampleModalLabel"
            >
              Back
            </h5>
            <button
              type="button"
              class="btn-close"
              data-bs-dismiss="modal"
              aria-label="Закрыть"
              style="margin-right: 3%; margin-top: 3%"
            ></button>
          </div>
          <div style="left: 0" class="modal-body">
            <div
              class="container"
              style="
                display: flex;
                justify-content: center;
                align-items: center;
              "
            >
              <form>
                <div class="mb-3">
                  <h1 style="margin-left: 32%">Account login</h1>
                </div>
               
                <div style="width: 60%;margin-left: 24%">
                    <p style="font-style: normal;font-weight: 500;font-size: 16px;line-height: 120%;color: #B81414;">Incorrect e-mail address or password. Please try again.</p>
                </div>
                <div class="mb-4">
                  <label
                    style="
                      font-size: 19px;
                      color: rgba(29, 32, 36, 1);
                      margin-top: 45px;
                      margin-left: 11%;
                    "
                    for="validationServerUsername" class="form-label"
                    >Email</label
                  >
                  <input
                    style="
                      width: 77%;
                      height: 70px;
                      background: #f1f5f8;
                      border-radius: 13px;
                      margin-left: 11%;
                    "
                   
                    type="email"
                   
                   
                    placeholder="Please enter your valid e-mail address"
                    class="form-control is-invalid" id="validationServerUsername" aria-describedby="inputGroupPrepend3 validationServerUsernameFeedback" required
                  />
                </div>

                <div class="mb-3">
                  <label
                    style="font-size: 19px; margin-left: 11%"
                    for="exampleInputPassword1"
                    class="form-label"
                    >Password</label
                  >
                  <input
                    style="
                      width: 77%;
                      height: 70px;
                      border-radius: 13px;
                      background: #f1f5f8;
                      margin-left: 11%;
                    "
                    type="password"
                    class="form-control is-invalid" id="validationServerUsername" aria-describedby="inputGroupPrepend3 validationServerUsernameFeedback" required
                  
                    placeholder="Please enter password"
                  />
                  <div
                    id="emailHelp"
                    class="form-text"
                    style="
                      font-size: 16px;
                      font-family: 'Ubuntu';
                      font-weight: 300;
                      line-height: 150%;
                      font-style: normal;
                      margin-top: 1%;
                      margin-left: 11%;
                    "
                  >
                    The password must be at least 8 characters long and must
                    include numbers, uppercase and lowercase letters.
                  </div>
                </div>
                <div style="display: flex">
                  <div class="form-check" style="margin-left: 12%; width: 60%">
                    <input
                      class="form-check-input"
                      type="checkbox"
                      value=""
                      id="flexCheckDefault"
                      style="background: #1d2024"
                    />
                    <label
                      class="form-check-label"
                      for="flexCheckDefault"
                      style="font-size: 18px; margin-left: 2%"
                    >
                     Remember me
                    </label>
                  </div>

                  <div style="width: 60%; margin-left: 10%">
                    <button
                      style=""
                      class="btn btn-link"
                      data-bs-target="#exampleModalToggle2"
                      data-bs-toggle="modal"
                      data-bs-dismiss="modal"
                    >
                      <p
                        style="
                          font-style: normal;
                          font-weight: 500;
                          font-size: 14px;
                          line-height: 120%;
                          text-decoration-line: underline;
                          color: #989fa1;
                        "
                      >
                        Forgot your password?
                      </p>
                    </button>
                  </div>
                </div>

                <div>
                  <button
                    style="
                      background: #1d2024;
                      width: 77%;
                      height: 86px;
                      border-radius: 48px;
                      margin-top: 6%;
                      font-size: 29px;
                      margin-left: 11%;
                    "
                    type="submit"
                    class="btn btn-primary"
                  >
                    Submit
                  </button>
                </div>

                <div
                  style="
                    color: #989fa1;
                    font-size: 18px;
                    display: flex;
                    justify-content: center;
                    margin-top: 9%;
                    align-items: center;
                    margin-right: ;
                  "
                >
                  <div
                    style="
                      border: 1.34579px solid #989fa1;
                      width: 28%;
                      margin-right: 2%;
                      margin-top: 1%;
                    "
                  ></div>
                  Or sign up with
                  <div
                    style="
                      border: 1.34579px solid #989fa1;
                      width: 28%;
                      margin-left: 2%;
                      margin-top: 1%;
                    "
                  ></div>
                </div>

                <div style="margin-top: 9%">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="10%"
                    height="5%"
                    fill="currentColor"
                    class="bi bi-apple"
                    viewBox="0 0 16 16"
                    style="margin-left: 10%"
                  >
                    <path
                      d="M11.182.008C11.148-.03 9.923.023 8.857 1.18c-1.066 1.156-.902 2.482-.878 2.516.024.034 1.52.087 2.475-1.258.955-1.345.762-2.391.728-2.43Zm3.314 11.733c-.048-.096-2.325-1.234-2.113-3.422.212-2.189 1.675-2.789 1.698-2.854.023-.065-.597-.79-1.254-1.157a3.692 3.692 0 0 0-1.563-.434c-.108-.003-.483-.095-1.254.116-.508.139-1.653.589-1.968.607-.316.018-1.256-.522-2.267-.665-.647-.125-1.333.131-1.824.328-.49.196-1.422.754-2.074 2.237-.652 1.482-.311 3.83-.067 4.56.244.729.625 1.924 1.273 2.796.576.984 1.34 1.667 1.659 1.899.319.232 1.219.386 1.843.067.502-.308 1.408-.485 1.766-.472.357.013 1.061.154 1.782.539.571.197 1.111.115 1.652-.105.541-.221 1.324-1.059 2.238-2.758.347-.79.505-1.217.473-1.282Z"
                    />
                    <path
                      d="M11.182.008C11.148-.03 9.923.023 8.857 1.18c-1.066 1.156-.902 2.482-.878 2.516.024.034 1.52.087 2.475-1.258.955-1.345.762-2.391.728-2.43Zm3.314 11.733c-.048-.096-2.325-1.234-2.113-3.422.212-2.189 1.675-2.789 1.698-2.854.023-.065-.597-.79-1.254-1.157a3.692 3.692 0 0 0-1.563-.434c-.108-.003-.483-.095-1.254.116-.508.139-1.653.589-1.968.607-.316.018-1.256-.522-2.267-.665-.647-.125-1.333.131-1.824.328-.49.196-1.422.754-2.074 2.237-.652 1.482-.311 3.83-.067 4.56.244.729.625 1.924 1.273 2.796.576.984 1.34 1.667 1.659 1.899.319.232 1.219.386 1.843.067.502-.308 1.408-.485 1.766-.472.357.013 1.061.154 1.782.539.571.197 1.111.115 1.652-.105.541-.221 1.324-1.059 2.238-2.758.347-.79.505-1.217.473-1.282Z"
                    />
                  </svg>

                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="10%"
                    height="5%"
                    fill="currentColor"
                    class="bi bi-google"
                    viewBox="0 0 16 16"
                    style="margin-left: 7%"
                  >
                    <path
                      d="M15.545 6.558a9.42 9.42 0 0 1 .139 1.626c0 2.434-.87 4.492-2.384 5.885h.002C11.978 15.292 10.158 16 8 16A8 8 0 1 1 8 0a7.689 7.689 0 0 1 5.352 2.082l-2.284 2.284A4.347 4.347 0 0 0 8 3.166c-2.087 0-3.86 1.408-4.492 3.304a4.792 4.792 0 0 0 0 3.063h.003c.635 1.893 2.405 3.301 4.492 3.301 1.078 0 2.004-.276 2.722-.764h-.003a3.702 3.702 0 0 0 1.599-2.431H8v-3.08h7.545z"
                    />
                  </svg>

                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="10%"
                    height="5%"
                    fill="currentColor"
                    class="bi bi-facebook"
                    viewBox="0 0 16 16"
                    style="margin-left: 7%"
                  >
                    <path
                      d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z"
                    />
                  </svg>

                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="10%"
                    height="5%"
                    fill="currentColor"
                    class="bi bi-twitter"
                    viewBox="0 0 16 16"
                    style="margin-left: 7%"
                  >
                    <path
                      d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z"
                    />
                  </svg>

                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="10%"
                    height="5%"
                    fill="currentColor"
                    class="bi bi-bookmarks-fill"
                    viewBox="0 0 16 16"
                    style="margin-left: 7%"
                  >
                    <path
                      d="M2 4a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v11.5a.5.5 0 0 1-.777.416L7 13.101l-4.223 2.815A.5.5 0 0 1 2 15.5V4z"
                    />
                    <path
                      d="M4.268 1A2 2 0 0 1 6 0h6a2 2 0 0 1 2 2v11.5a.5.5 0 0 1-.777.416L13 13.768V2a1 1 0 0 0-1-1H4.268z"
                    />
                  </svg>
                </div>

                <div style="margin-top: 9%; margin-left: 27%">
                  <div style="font-size: 19px">
                    Already have an account?
                    <link
                      style="background-color: orange; color: red"
                      class="text-danger"
                    />Sign in up here<link />
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div
    class="modal fade"
    id="exampleModalToggle2"
    aria-hidden="true"
    aria-labelledby="exampleModalToggleLabel2"
    tabindex="-1"
  >
    <div class="modal-dialog">
      <div
        class="modal-content"
        style="
          width: 114%;
          height: 485.38px;
          background: #ffffff;
          box-shadow: 0px 0px 35px rgba(0, 0, 0, 0.2);
          border-radius: 50px;
        "
      >
        <div class="modal-header">
          <h5
            style="
              margin-left: 3%;
              margin-top: 1%;
              font-style: normal;
              font-weight: 400;
              font-size: 14px;
              line-height: 120%;
              /* identical to box height, or 17px */

              display: flex;
              align-items: center;

              color: #989fa1;
            "
            class="modal-title"
            id="exampleModalToggleLabel2"
          >
            Back
          </h5>

          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="modal"
            aria-label="Close"
            style="margin-top: 2%; margin-right: 2%"
          ></button>
        </div>
        <div class="modal-body">
          <div
            style="
              margin-left: 1%;
              display: flex;
              justify-content: center;
              align-items: center;
            "
          >
            <h1>Password recovery</h1>
          </div>
          <div style="margin-left: 9%; width: 78%; margin-top: 1%">
            <p
              style="
                font-style: normal;
                font-weight: 300;
                font-size: 16px;
                line-height: 150%;
              "
            >
              Please enter e-mail you specified during registration and we will
              send you a new password.
            </p>
          </div>
          <div class="" style="margin-left: 9%">
            <div class="mb-4">
              <label
                style="
                  font-size: 19px;
                  color: rgba(29, 32, 36, 1);
                  margin-top: 35px;
                "
                for="exampleInputEmail1"
                class="form-label"
                >Email</label
              >
              <input
                style="
                  height: 70px;
                  background: #f1f5f8;
                  border-radius: 13px;

                  width: 93%;
                "
                type="email"
                class="form-control"
                id="exampleInputEmail1"
                aria-describedby="emailHelp"
                placeholder="Please enter your valid e-mail address"
              />
            </div>
          </div>
          <div style="margin-left: 8.5%; display: flex; align-items: center">
            <button
              class="btn btn-primary"
              data-bs-target="#exampleModalToggle3"
              data-bs-toggle="modal"
              
              style="
                width: 93%;
                height: 64px;
                background: #1d2024;
                border-radius: 35px;
                color: #ffffff;
              "
            >
              <p
                style="
                  font-style: normal;
                  font-weight: 500;
                  font-size: 22px;
                  line-height: 200%;
                  margin-top: 2%;
                "
              >
                Send
              </p>
            </button>
          </div>
        </div>
      </div>
    </div>

  </div>    <div
      
      class="modal fade"
      id="exampleModalToggle3"
      tabindex="-1"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
    <div class="modal-dialog">
      <div
        class="modal-content"
        style="
          width: 114%;
          height: 264.13px;
          background: #ffffff;
          box-shadow: 0px 0px 35px rgba(0, 0, 0, 0.2);
          border-radius: 50px;
        "
      >
        <div class="modal-header">
          <h5
            style="
              margin-top: 2%;
              margin-left: 3%;
              font-style: normal;
              font-weight: 400;
              font-size: 14px;
              line-height: 120%;
              color: #989fa1;
            "
            class="modal-title"
            id="exampleModalLabel"
          >
            Back
          </h5>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="modal"
            aria-label="Close"
            style="margin-right: 3%; margin-top: 1%"
          ></button>
        </div>
        <div class="modal-body" style="">
          <div class="container">
            <div
              style="
                margin-left: 1%;
                display: flex;
                justify-content: center;
                align-items: center;
              "
            >
              <h1>Password recovery</h1>
            </div>
            <div
              style="
                margin-left: 9%;
                width: 82%;
                margin-top: 1%;
                display: flex;
                align-items: center;
                text-align: center;
              "
            >
              <p
                style="
                  font-style: normal;
                  font-weight: 300;
                  font-size: 16px;
                  line-height: 150%;
                "
              >
                We have sent you a letter with a password recovery link. Please
                check your e-mail.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    </div>

  <a
    style="
      width: 21%;
      height: 64px;
      border: 1px solid #1d2024;
      border-radius: 35px;
      background: #ffffff;
    "
    class="btn btn-primary"
    data-bs-toggle="modal"
    href="#exampleModalToggle"
    role="button"
    ><p
      style="
        font-style: normal;
        font-weight: 500;
        font-size: 24px;
        line-height: 200%;
        /* identical to box height, or 48px */

        color: #1d2024;
      "
    >
      Sign in
    </p></a
  >
</template>
<script>

export default {
  components: {
    
  },
  data() {
    return {
      isActive: false,
    };
  },
  emits: ["onclose"],
  methods: {
    onclose() {
      this.$emit("onclose");
    },
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
