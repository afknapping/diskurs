# Principles, constraints, concepts

- must work well on older e-ink device
- quantity numbers are love metric competitions (amount of likes, answers to post, etc). "amount of words per threat" might be another, more subject-based angle instead of reactions of others
  - it would be weird to not offer "number of answers in thread" because people are used to that and probably expect it. but using number of words would be worth a try as default imo. if people don't use it and switch to anount-of-answers, ok then
  - it would be ok imo to simply not show love metric competition numbers. you like something and that is all you see. maybe as author you can look at a list of people who reacted but it shows the numbers nowhere
- per default, the site is completely grey-filtered. that way, people can use emoji without getting colorshocked
- keep as mfuch reference as possible
- image lightboxes: ui should distinguish between landscape and portrait in comparison to format of device
  - are they needed at all in 1.0? they *do* add to the desktop experience and this will be used a lot on laptops
- hanging punctuation is limited, but lists and quotes can be done
- split `like` into "great point" and "thx for sharing" to give a tiny bit of nuance
  - those can also be used as filters and for highlighting
  - people probably expect a simple like too, but the split version should be a default as an experiment
- "i want to read other things by this person"
- dis-curse. an authentic conversation cleanses you from the curse of assumptions and other undelivered communication
- badges: keep very small and focused on what fosters good conversation. "read guidelines" is a good badge to have, "has guidelines" would be a good badge for a forum to have
- what fosters good conversation for people who never used a forum, and who are new to urbit?
- is flagging/snitching needed for a 1.0? does that need to me automated? does it need to be persisted? why make that easy? if it is really so upsetting that you want to call the authorities, send them a DM with a link to the post and write a sentence or two on what you wish should happen next
- There should be a clear prioritisation on what delivers the most value
  - Since there is no innovation to do inititally, the emphasis should be on quality of functionality, not quantity (Half, Not Half-Assed)
- content-based, not screen-based "media queries" first, where possible – see [Inside-out Design](https://codepen.io/afknapping/pen/MwNbGz)
- markup should be hackable and somewhat stable. state classes should be added to most outer related element. custom css is not needed for 1.0
- everything must behave nicely when base font size is zoomed
  - zoom ui is important, because there is no quick scaling for mobile browsers
- it should work as PWA or electron app without browser chrome → needs back buttons then
  - is that detectable with css/js?




(This is a living document. All feedback and challenges are welcome)
