---
title: 联系我们
date: 2022-10-24
type: landing

sections:
  - block: contact
    content:
      title: 联系我们
      text: |
        欢迎与我们交流科研合作、人才培养及学术交流等事宜。
      email: test@example.org
      phone: ''
      address:
        street: 深圳市光明区新湖街道公常路66号中山大学深圳校区
        city: 深圳市
        region: 广东省
        postcode: '518107'
        country: 中国
        country_code: CN
      directions: 欢迎提前联系，我们将为您提供详细到访指引。
      office_hours:
        - '周一至周五 09:00 至 17:00'
      appointment_url: ''
      autolink: true
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title: 中山大学深圳校区地图
      subtitle: ''
      text: |
        {{< campus-map >}}
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image:
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
