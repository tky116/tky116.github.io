---
# ホームページのタイトル（空にするとサイトタイトルが使用される）
title: ''
date: 2024-03-09
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      username: admin
  
  - block: experience
    id: experience
    content:
      title: 経験
      date_format: 2006年1月
      items:
        - title: ソフトウェアエンジニア
          company: 株式会社○○
          company_url: ''
          location: 東京
          date_start: '2020-01-01'
          date_end: ''
          description: |2-
              主な職務:
              
              * バックエンド開発
              * クラウドインフラ構築
              * チームリード
    design:
      columns: '2'
  
  - block: portfolio
    id: projects
    content:
      title: Projects
      subtitle: 成果物
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: すべて
          tag: '*'
        - name: Web開発
          tag: Web
        - name: その他
          tag: Other
    design:
      columns: '2'
      view: showcase
  
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: '問い合わせ'
      email: tky.tky.116@gmail.com
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Twitter
          link: 'https://twitter.com/dot_asterisk'
      autolink: true
    design:
      columns: '2'
---