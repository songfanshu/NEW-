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
      phone: 888 888 88 88
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
      directions: 进入大楼后沿楼梯前往二楼办公室
      office_hours:
        - '周一 10:00 至 13:00'
        - '周三 09:00 至 10:00'
      appointment_url: 'https://calendly.com'
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
