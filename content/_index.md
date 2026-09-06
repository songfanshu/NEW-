title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        先进集成电路材料与类脑芯片课题组
        材料与光电信息研究
      image:
        filename: welcome.jpg
      text: |
        <br>
        专注于先进材料、光电器件、类脑芯片与智能感知等方向的科学研究与人才培养。

  - block: collection
    content:
      title: 课题组动态
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  - block: markdown
    content:
      title: 团队建设
      text: |
        欢迎了解我们的科研工作、团队建设与学术活动。
    design:
      columns: '1'
      background:
        image:
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: 研究成果
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title: 首页
      text: |
        {{% cta cta_link="./people/" cta_text="查看团队成员 →" %}}
    design:
      columns: '1'
