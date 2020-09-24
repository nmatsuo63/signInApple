<template>
  <div>
    <div>
      <h2>サインインしていないと見えない情報です</h2>
      <img :src="$auth.user.picture" />
      <h3>ユーザ名：{{ $auth.user.name }}</h3>
      <p>メールアドレス：{{ $auth.user.email }}</p>
    </div>

    <!-- <div>
      <pre>{{ JSON.stringify($auth.user, null, 2) }}</pre>
    </div> -->
  </div>
</template>
