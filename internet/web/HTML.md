https://news.ycombinator.com/item?id=25701053

susam [–]

Note that closing </p> tags are optional†, so one can be an HTML purist and still write a decent HTML document with a relatively clean markup like this:

    <!DOCTYPE html>
    <html lang="en">
    <title>Lorem Ipsum</title>
    <p>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    Duis id maximus tortor. Sed nisi ante, fermentum vel nunc
    et, tincidunt sagittis magna. In ultrices commodo lacus, id
    tristique ipsum euismod laoreet.
    <p>
    Maecenas at neque posuere, aliquet erat at, vehicula est.
    Duis aliquet elit et arcu laoreet, id pulvinar eros pretium.
    Quisque consectetur, enim semper facilisis feugiat, velit
    sapien semper arcu, eu mollis libero est et odio.
    <p>
    Curabitur fringilla interdum ante vel ultricies. Mauris
    volutpat nisi sed turpis elementum elementum. Mauris nec
    eleifend lorem. Sed ac vulputate libero.

A valid HTML5 document does not require† explicit <head>, <body>, or the closing </p>, </html> tags. See https://html.spec.whatwg.org/#optional-tags for more details.

Similarly, the markup for lists and tables can be cleaned up too because the closing </li>, </tr>, </th>, </td> tags are optional†.

Note that the opening <html> tag is optional† too but I retained it in the above example to specify the lang attribute otherwise the W3 markup validator warns, "Consider adding a lang attribute to the html start tag to declare the language of this document."

† These tags are optional provided certain conditions are met. See the spec for full details. In practice, one almost never has to worry about these conditions. 

https://paulkinchla.com/blog/javascript-is-a-ghost/

https://css-tricks.com/using-details-for-menus-and-dialogs-is-an-interesting-idea/
> https://news.ycombinator.com/item?id=26915706

https://www.matuzo.at/blog/html-boilerplate/
> https://news.ycombinator.com/item?id=26952557

https://markodenic.com/html-tips/
> https://news.ycombinator.com/item?id=27054348

https://localghost.dev/2021/06/the-right-tag-for-the-job-why-you-should-use-semantic-html/
> https://news.ycombinator.com/item?id=27414183

https://learn-the-web.algonquindesign.ca/topics/html-semantics-cheat-sheet/

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/datalist
> https://news.ycombinator.com/item?id=27602699

https://www.nayuki.io/page/practical-guide-to-xhtml

# Rich Text Editors - WYSIWYG
https://codemirror.net/
> https://prosemirror.net/

https://github.com/tinymce/tinymce

https://www.tiptap.dev/
> https://news.ycombinator.com/item?id=26901975

https://editorjs.io/

http://john.ankarstrom.se/html/
> https://news.ycombinator.com/item?id=26723408

https://docs.slatejs.org/

https://github.com/michelson/dante

https://en.wikipedia.org/wiki/Markdown

https://www.w3.org/Amaya/

https://web.archive.org/web/20140310190221/http://www.sewingandembroiderywarehouse.com/embtrb.htm
> https://news.ycombinator.com/item?id=28052190

https://nolanlawson.com/2021/08/08/improving-responsiveness-in-text-inputs/
> https://news.ycombinator.com/item?id=28107364

https://www.ashbyhq.com/blog/company/tiptap-part-1
> https://news.ycombinator.com/item?id=30299800

https://news.ycombinator.com/item?id=30673759

# DOM
https://en.wikipedia.org/wiki/Document_Object_Model
https://domevents.dev/

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ruby Represents small annotations that are rendered above,
> https://news.ycombinator.com/item?id=27999898
> https://news.ycombinator.com/item?id=29441857

# Security
https://korben.info/exploit-fichier-texte-txt-macos.html

https://developer.mozilla.org/en-US/docs/Web/API/HTML_Sanitizer_API
> https://news.ycombinator.com/item?id=27061020

# Body
https://atfzl.com/don-t-attach-tooltips-to-document-body
> https://news.ycombinator.com/item?id=28230977

# Link
https://www.jefftk.com/p/why-prefetch-is-broken
> https://news.ycombinator.com/item?id=27365608

https://blog.ledez.net/informatique/tips/redirection-html/

# Tools
https://en.wikipedia.org/wiki/Dynamic_HTML

https://remaketheweb.com/
> https://news.ycombinator.com/item?id=27148097
> https://github.com/remake/remake-framework

# Parser
https://htmlparser.info/
> https://news.ycombinator.com/item?id=27311627

https://bien.ee/a-contenteditable-pasted-garbage-and-caret-placement-walk-into-a-pub/
> https://news.ycombinator.com/item?id=27924970

# Checkbox
https://www.bryanbraun.com/checkboxland/
> https://news.ycombinator.com/item?id=28489791
> https://www.bryanbraun.com/2020/06/06/checkboxland/

# History
https://zachholman.com/posts/only-90s-developers/
> https://news.ycombinator.com/item?id=29296003

# News
https://www.smashingmagazine.com/2022/03/html-attributes-you-never-use/

https://github.com/ludovicianul/hq

https://github.com/gildas-lormeau/SingleFile
> https://news.ycombinator.com/item?id=30527999

https://en.wikipedia.org/wiki/Progressive_enhancement
> https://technology.blog.gov.uk/2016/09/19/why-we-use-progressive-enhancement-to-build-gov-uk/
> > https://news.ycombinator.com/item?id=12538144

https://andrewpillar.com/programming/2022/02/26/req-an-http-scripting-language/ go
> https://github.com/andrewpillar/req

https://css-tricks.com/explain-the-first-10-lines-of-twitter-source-code/
> https://news.ycombinator.com/item?id=30464350

https://devapt.com/html-tags
> https://news.ycombinator.com/item?id=30469695

https://thenewstack.io/htmx-html-approach-to-interactivity-in-a-javascript-world/

https://webkit.org/blog/12209/introducing-the-dialog-element/

https://www.scottohara.me/blog/2022/01/20/divisive.html

https://blog.scottlogic.com/2022/01/20/noJS-making-a-calculator-in-pure-css-html.html
> https://news.ycombinator.com/item?id=30021058

https://html.energy/
> https://news.ycombinator.com/item?id=29942463

https://css-tricks.com/a-whole-website-in-a-single-html-file/
> https://news.ycombinator.com/item?id=29668260

https://www.ctrl.blog/entry/html-responsive-video.html
> https://news.ycombinator.com/item?id=29024868

https://github.com/WebKit/explainers/tree/main/model
> https://news.ycombinator.com/item?id=28353997

https://news.ycombinator.com/item?id=28055160

