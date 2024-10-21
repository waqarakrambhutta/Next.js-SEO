**<span style="text-decoration:underline;">#Next.js SEO</span>**

**<span style="text-decoration:underline;">To run website of localhost on internet globally we use [Link](docs.srv.us).</span>**

**Steps:**



* **Metadata:** Title, Description and favicon.ico(generate favicon from the [link](realfavicongenerator.net)). We can set meta data as: \



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



* **opengraph-image.png:** this is the link image when we paste the link of the website on social media. This is a simple png. You can use [Link](gimp.org) for it.


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
