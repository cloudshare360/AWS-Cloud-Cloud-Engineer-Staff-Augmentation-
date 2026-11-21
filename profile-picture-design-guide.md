# AWS Cloud Agentic Development Engineer — Profile Picture Design Guide

## ⚠️ Important: GitHub Profile Picture Requirements

**GitHub does NOT support SVG files** for profile picture uploads. You must convert the SVG to PNG, JPG, or GIF before uploading.

| Specification | Requirement |
|--------------|-------------|
| **Supported formats** | PNG, JPG, GIF (SVG not supported) |
| **Recommended size** | 512×512 pixels (minimum 256×256) |
| **Maximum file size** | 1 MB |
| **Shape** | Square (GitHub applies circular crop) |
| **Background** | Transparent PNG works best |

---

## Step 1: Convert SVG to PNG (Required for GitHub)

Convert `aws-cloud-engineer-profile.svg` to PNG using one of these methods:

### Option A: Online Converter (Easiest)
1. Go to [svgtopng.com](https://svgtopng.com) or [cloudconvert.com](https://cloudconvert.com)
2. Upload `aws-cloud-engineer-profile.svg`
3. Set output size to **512×512 pixels**
4. Download as PNG

### Option B: Command Line (if you have `rsvg-convert` installed)
```bash
rsvg-convert -w 512 -h 512 -o aws-cloud-engineer-profile.png aws-cloud-engineer-profile.svg
```

### Option C: Design Tools
1. Open the SVG in **Figma**, **Adobe Illustrator**, or **Inkscape**
2. Export/Save As PNG at **512×512 pixels**
3. Ensure background is transparent (if supported)

---

## Step 2: Upload to GitHub Profile

1. Go to **github.com/settings/profile**
2. Click on your current profile picture or the camera icon
3. Click **"Upload new picture"**
4. Select the PNG file you created (`aws-cloud-engineer-profile.png`)
5. Adjust the crop circle to center the design
6. Click **"Apply changes"**
7. Click **"Update profile"** to save

---

## SVG Profile Picture (Source File)

**File:** `aws-cloud-engineer-profile.svg`  
**Format:** SVG (Scalable Vector Graphics) — 512×512 px  
**Usage:** Source file for converting to PNG. Use directly on platforms that support SVG (LinkedIn, email signatures, websites, etc.)

The SVG features:
- **AWS dark blue background** (`#232F3E`) with subtle gradient
- **AWS orange accent** (`#FF9900`) for the cloud symbol and highlights
- **Central badge** with "AWS" text and "Cloud Engineer" subtitle
- **Stylized AWS cloud symbol** above the text
- **5 role segments** around the outer ring: Developer (Lambda), DevOps (CodePipeline), Operations (CloudWatch), Pre-Production (CodeBuild), Post-Production (Health)
- **6 tech stack icons** in the inner ring: AWS, React, Node.js, Python, Angular, GitLab
- **Professional, clean design** suitable for corporate profiles

---

## AI Image Generation Prompt

If you want a photorealistic or illustrated profile picture, use this prompt with tools like Midjourney, DALL-E 3, or Stable Diffusion:

> **Prompt:**
> Professional profile picture of an AWS Cloud Agentic Development Engineer, modern tech portrait, clean corporate style, person wearing business casual attire, subtle AWS cloud elements in background, AWS orange (#FF9900) and dark navy (#232F3E) color palette, soft studio lighting, shallow depth of field, circular crop, high resolution, 8k, photorealistic, tech professional, confident expression, minimal background with abstract cloud computing motifs --ar 1:1 --style raw --v 6

> **Negative Prompt (if supported):**
> blurry, low resolution, cartoon, anime, cluttered background, multiple people, text watermarks, distorted face, oversaturated

---

## Design Elements Reference (from README & Role Details)

| Element | Source | Design Translation |
|---------|--------|-------------------|
| Role | AWS Cloud Agentic Development Engineer | AWS branding, cloud motif, agentic AI tools |
| Engagement | Staff Augmentation | Professional, hireable appearance |
| Skills | DevOps, Development, Operations, Testing, AI Agent Dev | Tech professional, modern tools aesthetic |
| Rate | $50–$60/hr | Mid-to-senior level professional look |
| Contact | cloud.share360@gmail.com | Corporate, approachable feel |

---

## Recommended Usage

| Platform | Recommended Format | Size | Notes |
|----------|-------------------|------|-------|
| **GitHub** | **PNG** (convert from SVG) | **512×512 px** | Max 1 MB, circular crop applied |
| LinkedIn | PNG or SVG | 400×400 px | Circular crop applied by platform |
| Email signature | PNG or SVG | 200×200 px | Transparent background works well |
| Resume/CV | PNG | 200×200 px | Print-friendly, smaller file size |
| Website/Portfolio | SVG or PNG | 512×512 px | SVG scales without quality loss |

---

## Quick Conversion Commands

```bash
# Using ImageMagick (if installed)
convert aws-cloud-engineer-profile.svg -resize 512x512 aws-cloud-engineer-profile.png

# Using rsvg-convert (if installed)
rsvg-convert -w 512 -h 512 -o aws-cloud-engineer-profile.png aws-cloud-engineer-profile.svg

# Using Inkscape (if installed)
inkscape aws-cloud-engineer-profile.svg --export-png=aws-cloud-engineer-profile.png -w 512 -h 512
```

---

