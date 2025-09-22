# Hugoplate Building Blocks (Atomic Design Lens)

## Pages (pre-designed routes)

These are full-page templates. They stitch together sections/modules.

- Homepage: uses hero + services/features + CTA + testimonials etc.
- About: text/image split, story, team section.
- Contact: contact form (Formspree/Airform endpoint).
- Authors: list of all authors (for blogs).
- Author Single: bio + posts by that author.
- Blog: list of posts with blog-card components.
- Blog Single: full post template (includes author card, pagination).
- Custom 404: “page not found” template with CTA to go home.
- Elements: showcase page that demonstrates all available elements/shortcodes.
- Privacy Policy: legal text page.
- Tags: list of tags.
- Tag Single: posts under one tag.
- Categories: list of categories.
- Category Single: posts under one category.
- Search: results page powered by the search module.

## Sections / Modules (lego blocks within pages)

These are the configurable sections you can enable, disable, and reorder in `params.toml`.

- Hero section (headline, subheadline, button, often with background image).
- Call-to-Action (CTA) section:
    - Variant A: text + button.
    - Variant B: headline + three bulletpoints + button.
- Features/Services grid (cards with icon + text, for listing offerings).
- Testimonials (usually 3-item quotes).
- Pricing table (3-column layout with plan features).
- FAQ accordion (collapsible Q&A).
- Team section (author/team cards reused).
- Contact section (form).
- Announcement bar (dismissible promo/notice).
- Cookie consent banner.
- Subscription block (Mailchimp integration).
- Social share strip.
- Preloader (loading animation).
- Gallery (image grid).
- Slider (image carousel).
- Blog list (reused on homepage or as section).
- Tabs (tabbed content).
- Modal (popup).
- Table of contents (auto-generated nav for a page).
- Video embed block (YouTube, Vimeo, or custom mp4).
- Code/syntax highlighting block (for posts with code).
- Map block (Google Maps embed, toggleable).

## Components (reusable micro-pieces)

These are smaller snippets that modules and sections use.

- Author card (name, avatar, bio).
- Blog card (thumbnail, title, excerpt, tags).
- Breadcrumb (nav trail).
- Language switcher (for multilingual sites).
- Pagination (next/prev controls).
- Theme switcher (light/dark toggle).
- TW size indicator (debug tool for Tailwind breakpoints).
- Categories widget (list of categories, usually sidebar).
- Tags widget (tag cloud/list).
- Widget wrapper (styling shell for sidebar blocks).

## Essentials (global partials)

Always included, they scaffold every page.

- Head (meta tags, CSS links).
- Header (site navigation).
- Footer (bottom nav, copyright, social links).
- Script (JS includes).
- Style (global style includes).

## Elements (atomic pieces, parallel to Markdown/Notion basics)

You already know these primitives, but Hugoplate adds shortcodes for convenience.

- Headings (h1–h6).
- Paragraphs, emphasis (bold, italic), strikethrough.
- Links (inline, reference, relative).
- Lists (ordered, unordered).
- Blockquote.
- Horizontal rule.
- Code block (with syntax highlighting).
- Table.
- Image.
- Button shortcode (`{{< button >}}`).
- Notice shortcode (`note`, `tip`, `info`, `warning`).
- Tab shortcode (`{{< tab >}}`).
- Accordion shortcode (`{{< accordion >}}`).
- Gallery shortcode (`{{< gallery >}}`).
- Slider shortcode (`{{< slider >}}`).
- Video shortcode (`{{< video >}}`).
- YouTube shortcode (`{{< youtube >}}`).
- Mermaid diagram block (````mermaid`).

## Pages (Pre-Designed)

Hugoplate ships with ~15 pages prewired. They’re scaffolds that combine modules.

- Homepage → hero + features + CTA + testimonials.
- About → brand story, team.
- Contact → form.
- Authors/Author Single → bios + posts.
- Blog/Blog Single → list + detail view.
- Custom 404 → fallback page.
- Elements → demo page for shortcodes.
- Privacy Policy → boilerplate legal page.
- Tags/Tag Single → tag index + detail.
- Categories/Category Single → category index + detail.
- Search → results page.

Examples for this project:

- Landing page = Homepage, About, Contact, FAQ, Testimonials, Pricing.
- Portfolio = Blog + Blog Single, adapted with case studies as posts.


## **UX Portfolio Specifics**

### **Using "Blog" format in HugoPlate as Portfolio Gallery, each case study is one "blog post"**

Each case study = blog post with:

- Title
- Featured image
- Tags/categories
- Excerpt

These render as **cards** (blog-card component) on the Blog page.

- This replicates your Notion inline database gallery view.

### **Tags/Categories as Filters**

Use tags for methods/skills, categories for project types.

- Lets recruiters filter quickly.

### **Related Posts (Similar Posts)**

At end of a case study, auto-suggest related case studies by tag/category.

### **Search**

Scope it to posts/case studies for keyword lookup.

### **Cards**

You can reuse blog cards or author cards for case studies. Blog cards are better because they natively support featured images.