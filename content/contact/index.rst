public: yes
location: contact
hide_contact: true
headline:
  - tagline: 'Let’s get to know each other…'
    type: 'Contact Us'
before:
  - include: 'contact/_form.html.j2'
    submit: 'Send!'
    next: 'contact/thanks/'
social:
  - icon: 'twitter'
    text: '@OddBird'
    url: 'http://twitter.com/oddbird'
    after: 'on Twitter'
  - icon: 'slack'
    text: 'OddBird Friends'
    url: 'http://friends.oddbird.net/'
    after: 'public Slack'
  - icon: 'mail'
    text: 'birds@oddbird.net'
    url: 'mailto:birds@oddbird.net'
    after: 'by Email'
summary: |
  .. wrap:: div
    :class: contact-intro

    .. callmacro:: birds/utility.macros.j2#face
      :author: 'miriam'

    **We’re always happy to talk** –
    whether you have a project in mind,
    or just want to say hi.
    Ask a question,
    inquire about `our packages`_,
    set up a free consultation,
    or invite us to `speak to your company or conference`_.
    `Miriam Suzanne`_
    will get back to you soon.

    .. _our packages: /work/services/
    .. _speak to your company or conference: /speaking/
    .. _Miriam Suzanne: /birds/#bird-miriam


Start a Conversation
====================

There are many ways to start a conversation with us,
so feel free to pick the one that is most comfortable to you:

.. callmacro:: contact/macros.j2#social
