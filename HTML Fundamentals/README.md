# HTML Fundamentals

## M1

### P1

- *Al Gore* was one of the main contributor in the creation of internet. ALPANET was the basic of internet.
- WWW or the world wide web was essentially created by *Tim Burners Lee*.
- The Internet is a global network of networks while the Web, also referred formally as World Wide Web (www) is collection of information which is accessed via the Internet. Another way to look at this difference is; the Internet is infrastructure while the Web is service on top of that infrastructure. Alternatively, the Internet can be viewed as a big book-store while the Web can be viewed as collection of books on that store. At a high level, we can even think of the Internet as hardware and the Web as software!

### P2

- Html was created to share research documents.
- Html is a markup language ie we create a document and mark them up with certain tags. These tags are ment to be processed by the client which in this case is the browser.
- **DOCTYPE** defines or declares to the browser(HTML parser) which version of HTML standard are you following. The <!DOCTYPE> declaration is not an HTML tag; it is an instruction to the web browser about what version of HTML the page is written in. Although the modern day browsers are smart enough to interpret the doctype even if you skip it, but the older version might have some issues. Hence it is always adviced and a best practice to provide the doctype. Please refer [this](https://www.w3schools.com/tags/tag_doctype.asp) link for detailed explanation. Also refer [this](https://www.w3.org/QA/2002/04/valid-dtd-list.html) for recommended list of DOCTYPE.
    - *Strict* doctype refers to a strict mode in which the depricated tags are not considered.
    - *Transitional* doctype refers to a transitional mode in which the depricated tags are also considered.
- **HTML** tag wraps all other tags in an html page except DOCTYPE. HTML is based on SGML(Standard Generalized Markup Language) which a standard/specification for creating a markup language. SGML is a kind of document type definition or DTD.
- **Head** tag wraps all the metadata tags. Metadata tags are the tags which help provide information to browser or search engines and don't help in displaying any content on the browser. **Document metadata**.
- **Body** tag is used to wrap data or content tags. Content tags are used to display content on the page. **Document data**.
- Omitting the html, head, and body tags is certainly allowed by the HTML specs. The underlying reason is that browsers have always sought to be consistent with existing web pages, and the very early versions of HTML didn't define those elements. When HTML 2.0 first did, it was done in a way that the tags would be inferred when missing. I often find it convenient to omit the tags when prototyping and especially when writing test cases as it helps keep the mark-up focused on the test in question. The inference process should create the elements in exactly the manner that you see in Firebug, and browsers are pretty consistent in doing that.
- The HTML DOM document object is the owner of all other objects in your web page. You can access an element object including "head" using the document object. You can consider document as the <Html> tag inside a html page.

### P3

- Please refer to the basic.html and html4.1static.html to see the difference between a valid and in-valid html. Also you can validate the html at [this](http://validator.w3.org/#validate_by_input+with_options) link.

### P4 

