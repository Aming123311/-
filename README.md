# -<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>个人主页 - Tokyo_tokyo_08</title>
  <style>
    body {
      margin: 0;
      font-family: "PingFang SC", "Helvetica Neue", Helvetica, Arial, sans-serif;
      background-color: #ffffff;
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 40px 20px;
    }

    .container {
      max-width: 600px;
      width: 100%;
      text-align: center;
    }

    img.avatar {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 20px;
      border: 3px solid #eee;
    }

    h1 {
      font-size: 2.2em;
      margin-bottom: 0.5em;
    }

    p.description {
      font-size: 1.1em;
      color: #555;
      margin-bottom: 2em;
    }

    .social-links {
      display: flex;
      flex-direction: column;
      gap: 16px;
    }

    .social-item {
      background-color: #f2f2f2;
      border-radius: 10px;
      padding: 14px 20px;
      text-align: left;
      display: flex;
      justify-content: space-between;
      align-items: center;
      transition: all 0.2s ease;
      cursor: pointer;
    }

    .social-item:hover {
      background-color: #e0e0e0;
    }

    .social-label {
      font-weight: bold;
      font-size: 1em;
    }

    .social-value {
      font-size: 1em;
      color: #0066cc;
      word-break: break-all;
    }

    @media (max-width: 600px) {
      .social-item {
        flex-direction: column;
        align-items: flex-start;
      }

      .social-value {
        margin-top: 4px;
      }
    }
  </style>
  <script>
    function copyWeChat() {
      navigator.clipboard.writeText("Tokyo_tokyo_08").then(function() {
        alert("微信号已复制到剪贴板！");
      }, function(err) {
        alert("复制失败，请手动复制。");
      });
    }
  </script>
</head>
<body>
  <div class="container">
    <img src="avatar.jpg" alt="头像" class="avatar">
    <h1>欢迎来到我的主页</h1>
    <p class="description">以下是我的社交账号信息，欢迎添加或关注我。</p>
    <div class="social-links">
      <div class="social-item" onclick="copyWeChat()">
        <span class="social-label">微信</span>
        <span class="social-value">点击复制：Tokyo_tokyo_08</span>
      </div>
      <a class="social-item" href="http://wpa.qq.com/msgrd?v=3&uin=1542996910&site=qq&menu=yes" target="_blank">
        <span class="social-label">QQ</span>
        <span class="social-value">1542996910</span>
      </a>
      <a class="social-item" href="https://www.douyin.com/user/Tokyo_tokyo_08" target="_blank">
        <span class="social-label">抖音</span>
        <span class="social-value">Tokyo_tokyo_08</span>
      </a>
      <a class="social-item" href="https://www.kuaishou.com/profile/Tokyo_tokyo_08" target="_blank">
        <span class="social-label">快手</span>
        <span class="social-value">Tokyo_tokyo_08</span>
      </a>
    </div>
  </div>
</body>
</html>