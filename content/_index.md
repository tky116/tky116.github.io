---
# ホームページのタイトル（空にするとサイトタイトルが使用される）
title: 'Portfolio'
date: 2025-03-08
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      username: admin

  - block: experience
    id: achievements
    content:
      title: Achievements & Certifications
      subtitle: 実績・資格
      date_format: 2006年1月
      items:
        - title: VRアカデミー賞・審査員特別賞 / VRフェス
          company: VRプロフェッショナルアカデミー第16期
          company_url: 'https://vrfes16.peatix.com/'
          location: ''
          date_start: '2025-03-01'
          date_end: '2025-03-01'
          description:
            VR描画+生成AIを使用したアプリを制作し、審査の結果、審査員特別賞を受賞しました！
        - title: 最優秀賞 / ハッカソン
          company: VRプロフェッショナルアカデミー第16期
          company_url: 'https://vracademy.jp/blog/16thhackathon/'
          location: ''
          date_start: '2024-11-30'
          date_end: '2024-12-14'
          description:
            レメディ・アンド・カンパニー株式会社様よりお題をいただきVRアプリを作成。
            審査の結果、最優秀賞を受賞しました！
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
        - name: XR
          tag: XR
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
        - icon: x-twitter
          icon_pack: fab
          name: X（Twitter）
          link: 'https://twitter.com/dot_asterisk'
      autolink: true
    design:
      columns: '2'
---