<!-----

You have some errors, warnings, or alerts. If you are using reckless mode, turn it off to see useful information and inline alerts.
* ERRORs: 0
* WARNINGs: 0
* ALERTS: 1

Conversion time: 0.61 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β40
* Mon Oct 21 2024 16:32:25 GMT-0700 (PDT)
* Source doc: Next.js SEO
* This document has images: check for >>>>>  gd2md-html alert:  inline image link in generated source and store images to your server. NOTE: Images in exported zip file from Google Docs may not appear in  the same order as they do in your doc. Please check the images!

----->


<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 0; WARNINGs: 0; ALERTS: 1.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>


**<span style="text-decoration:underline;">Next.js SEO</span>**

**<span style="text-decoration:underline;">To run website on localhost on internet we use [Link](docs.srv.us).</span>**

**Steps:**



* **Metadata: **Title, Description and favicon.ico(generate favicon from the [link](realfavicongenerator.net)). We can set meta data as: \



```
export const metadata: Metadata = {
 title: {
   default: "Kitchen Equipments",
   template: "%s - Kitchen Equipments",
 },
 description: "Every type of Kitchen Accessories is availabe on our site.",
 twitter: {
   card: "summary_large_image",
 },
};
```


And further in sub pages we’ll use metadata as:


```
export const metadata = {
 title: "Categories",
};

```



* **opengraph-image.png: **this is the link image when we paste the link of the website on social media. This is a simple png. You can use [Link](gimp.org) for it.



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")


To see the preview of the og-image and metadata on social media, first we live the local host as mentioned on top. And paste the link on a website like [link](socialsharepreview.com)  or [link](opengraph.xyz).  For more functionality of og-image see the docs of next.js og-image generation.



* Follow the metadata of the Next docs …generateMetadata…
* Next.js generateStaticParams is also its part because page loading speed also affects the SEO.

**(Dynamic Sitemaps)**

Read the documentation of Next.js sitemap. [Link](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/sitemap).


    **(Robots)**

See the [documentation](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/robots) of Next.js. Robots are used to specify the pages that we want to hide from the search. We can also extend the robots in the metadata, but they will not work until the route is not defined in robots.ts file.

**(Google search console)**

Google search console is the platform that tells us the analytics of our website accessed by the people. How many clicks are there? In how many searches the website appears. And other info.

We can also use vercel for this purpose, which have its analytics plan to purchase.
