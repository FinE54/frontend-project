<template>
  <div class="login-wrap flex w-full h-full">
    <div
      class="
        left-content
        w-[500px]
        h-full
        from-blue-300
        to-blue-900
        bg-gradient-to-b
      "
    ></div>
    <div class="right-wrap flex-1 h-full flex justify-center items-center p-4">
      <div class="login-inner w-[300px]">
        <div class="login-header">
          <h1 class="text-2xl font-bold">Login</h1>
          <h1 class="text-md text-gray-500">登录到系统</h1>
        </div>
        <div class="login-form-wrap mt-4">
          <form>
            <input
              type="text"
              name="username"
              class="rounded border w-full p-2 text-sm"
              placeholder="请输入登录账户"
            />
            <input
              type="password"
              name="password"
              class="rounded border w-full p-2 text-sm mt-2"
              placeholder="请输入登录密码"
            />
            <div class="login-btns-wrap mt-4">
              <div class="flex text-sm items-center justify-between">
                <div class="flex items-center">
                  <input type="checkbox" />
                  <span class="ml-1">记住账户</span>
                </div>
                <a href="#" class="text-blue-700">忘记密码</a>
              </div>
              <button
                type="submit"
                class="rounded bg-blue-500 text-white w-full p-2 text-sm mt-4"
              >
                立即登录
              </button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>