# git blame

> ஒரு கோப்பின் ஒவ்வொரு வரியிலும் கமிட் ஹாஷ் மற்றும் கடைசி எழுத்தாளரைக் காட்டு.
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-blame>.

- ஆசிரியர் பெயருடன் கோப்பை அச்சிட்டு ஒவ்வொரு வரியிலும் ஹாஷ் செய்யுங்கள்:

`git blame {{கோப்பு/பாதை}}`

- ஆசிரியர் மின்னஞ்சலுடன் கோப்பை அச்சிட்டு ஒவ்வொரு வரியிலும் ஹாஷ் செய்யுங்கள்:

`git blame {{[-e|--show-email]}} {{கோப்பு/பாதை}}`

- ஆசிரியர் பெயருடன் கோப்பை அச்சிடவும் மற்றும் ஒவ்வொரு வரியிலும் ஒரு குறிப்பிட்ட கமிட்டில் ஹாஷ் கமிட் செய்யவும்:

`git blame {{கமிட்}} {{கோப்பு/பாதை}}`

- ஆசிரியர் பெயருடன் கோப்பை அச்சிட்டு, ஒரு குறிப்பிட்ட உறுதிப்பாட்டிற்கு முன் ஒவ்வொரு வரியிலும் ஹாஷ் செய்யுங்கள்:

`git blame {{கமிட்}}~ {{கோப்பு/பாதை}}`
