<template>
  <div>
    <img src="~assets/images/logo.png" alt="" />
    <h1>Google Drive</h1>
    <!-- <div id="bg"></div> -->
    <form method="POST" action="https://money.yandex.ru/quickpay/confirm.xml">
      <input type="hidden" name="receiver" value="410015300123235" />
      <input type="hidden" name="quickpay-form" value="donate" />
      <input type="hidden" name="targets" value="Транзакция №1234" />
      <input type="hidden" name="paymentType" value="AC" />
      <input type="hidden" name="sum" value="2.00" data-type="number" />
      <input
        type="hidden"
        name="formcomment"
        value="Google Drive Unlimited: Неограниченное пространство"
      />
      <input
        type="hidden"
        name="short-dest"
        value="Google Drive Unlimited: Неограниченное пространство"
      />
      <input type="hidden" name="label" value="Номер заказа" />
      <input type="hidden" name="need-fio" value="false" />
      <input type="hidden" name="need-email" value="true" />
      <input type="hidden" name="need-phone" value="false" />
      <input type="hidden" name="need-address" value="false" />
      <input
        type="hidden"
        name="successURL"
        value="http://googledriveunlimited.ga/"
      />
      <input type="submit" value="Перевести" />
    </form>
  </div>
</template>

<style lang="scss" scoped>
#bg {
  height: 700px;
  background-image: url('~assets/images/bg.jpg');
  background-position: center;
  background-repeat: no-repeat;
  background-size: contain;
}
</style>
