<template>
  <!-- Кнопка-триггер модального окна -->
  <button
    type="button"
    class="btn btn-primary"
    data-bs-toggle="modal"
    data-bs-target="#exampleModal"
  >
    Запустите демо модального окна
  </button>

  <!-- Модальное окно -->
  <div class="modal-xl">
    <div
      class="modal fade"
      id="exampleModal"
      tabindex="-1"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog modal-lg">
        <div
          style="height: 120%; border-radius: 67px; flex-wrap: wrap"
          class="modal-content"
        >
          <div class="modal-header">
            <h5
              style="font-size: 18px; margin-left: 5%; margin-top: 3%"
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
                  <h1 style="margin-left: 24%">Password recovery</h1>
                </div>

                <div class="mb-4" style="margin-top: 10%;">
                  <label
                    style="font-size: 19px; margin-left: 11%"
                    for="exampleInputPassword1"
                    class="form-label"
                    >New password</label
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
                    class="form-control"
                    id="exampleInputEmail1"
                    aria-describedby="emailHelp"
                    placeholder="Please enter your valid e-mail address"
                  />
                </div>

                <div class="mb-3">
                  <label
                    style="
                      font-family: 'Ubuntu';
                      font-style: normal;
                      font-weight: 500;
                      font-size: 19px;
                      line-height: 120%;
                      margin-left: 11%;
                    "
                    for="exampleInputPassword1"
                    class="form-label"
                    >Confirm new password</label
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
                    class="form-control"
                    id="exampleInputPassword1"
                    placeholder="Please confirm new password"
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
                    Save
                  </button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script></script>

<style></style>
