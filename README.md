# Personal Blog System

A feature-rich blog system built with Jekyll, supporting Markdown, LaTeX, and tags.

## Features

- Full Markdown support
- LaTeX formula rendering
- Image and video embedding
- Tag system with tag cloud
- Responsive design
- Related posts
- Mobile-friendly

## Getting Started

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Start the development server:
   ```bash
   bundle exec jekyll serve
   ```

3. Visit `http://localhost:4000` in your browser

## Creating New Posts

1. Create a new file in the `_posts` directory with the format: `YYYY-MM-DD-title.md`
2. Add the following front matter at the top of your post:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD
   author: "Your Name"
   tags: [tag1, tag2, tag3]
   ---
   ```

## Adding Images and Videos

1. Place your media files in the `assets` directory:
   - Images: `assets/images/`
   - Videos: `assets/videos/`

2. Reference them in your posts:
   ```markdown
   ![Image Description](/assets/images/your-image.jpg)
   
   <video src="/assets/videos/your-video.mp4" controls>
     Your browser does not support the video tag.
   </video>
   ```

## Using LaTeX

1. Inline math: `$E = mc^2$`
2. Block math:
   ```markdown
   $$
   \int_a^b f(x) dx = F(b) - F(a)
   $$
   ```

## Managing Tags

1. Add tags to your post's front matter:
   ```yaml
   tags: [技术, 教程, 数学]
   ```

2. Tags will automatically generate:
   - Tag pages at `/tags/tag-name/`
   - Tag cloud with post counts
   - Related posts based on common tags

## Customization

- Edit `_config.yml` for site-wide settings
- Modify `assets/css/blog.css` for styling
- Update layouts in `_layouts/` directory

## Contributing

Feel free to submit issues and enhancement requests!

```bash
   bundle exec jekyll serve
   ```
