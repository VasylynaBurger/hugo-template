---
title: Getting Started with Hugo
weight: 1
---

# Getting Started with Hugo  

Hugo is one of the fastest and most flexible static site generators available today. This guide will help you get started and build your first Hugo site in just a few simple steps.  

## Step 1: Install Hugo  
To begin, you need to install Hugo on your system. Follow the instructions below based on your operating system:  

1. **Windows**:  
   - Download the Hugo binary from the [Hugo releases page](https://github.com/gohugoio/hugo/releases).  
   - Extract the binary and add it to your system's PATH.  

2. **macOS**:  
   - Install Hugo using Homebrew:  
     ```bash
     brew install hugo
     ```  

3. **Linux**:  
   - Use your package manager to install Hugo or download the binary from the Hugo releases page.  

To confirm the installation, run:  
```bash
hugo version
```  

## Step 2: Create a New Site
Create a new Hugo site with the following command:

```bash
hugo new site my-hugo-site
```  
Replace `my-hugo-site` with your desired project name.

## Step 3: Choose a Theme  
Hugo supports a wide range of themes. Follow these steps to set up a theme:  

1. Visit the [Hugo Themes](https://themes.gohugo.io/) page to find a theme you like.  
2. Download the chosen theme and place it in the `themes` directory of your Hugo project.  
3. Update the `config.toml` file in the root of your project to specify the theme:  
   ```toml
   theme = "your-theme-name"
    ```  

## Step 4: Add Content

Hugo makes it easy to create content using Markdown files. To add your first post, follow these steps:

1. Run the following command:

   ```bash
   hugo new posts/my-first-post.md
    ```

This creates a new Markdown file in the `content/posts` directory.

2. Open the file in your preferred text editor. You'll see a front matter section at the top, where you can set details like the title and date. Add your content below the front matter.

3. Save the file, and you're ready to preview it on your site!