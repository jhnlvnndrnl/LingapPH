# LingapPH

**Public Assistance Information Portal for Filipinos**

LingapPH is a web-based information portal designed to help Filipinos discover government assistance programs, understand their requirements, and find the appropriate government agencies to contact.

The platform aims to make public assistance information easier to access through a simple, organized, and user-friendly interface.

## Context Overview

| Item | Description |
|---|---|
| **Category** | Government and Public Services |
| **Subcategory** | Public Assistance Services |
| **Website Title** | LingapPH — Public Assistance Information Portal for Filipinos |
| **Purpose** | Government and official assistance websites can be difficult to find, especially when information is spread across different agencies and platforms. LingapPH gathers legitimate sources and organizes them into a simple starting point where Filipinos can discover assistance programs, understand available services, and find the appropriate government agency to contact. |

The name **LingapPH** combines *lingap*, meaning care or assistance, with **PH**, representing the Philippines. The project focuses on Philippine government services and public assistance information.

## References and Problem Basis

The problem addressed by LingapPH is supported by the continued need to make Philippine government information easier to discover, understand, and access. Government services and assistance details are distributed across different agencies, websites, and service categories, which can make it difficult for citizens to identify the correct source.

LingapPH uses [BetterGovPH](https://bettergov.ph/) as its primary web reference and inspiration. BetterGovPH organizes Philippine government services, guides, hotlines, and agency information in one searchable portal. Its mission to make government data more accessible, understandable, and actionable aligns with LingapPH's goal of gathering legitimate public assistance sources in one clear starting point.

The [Philippine National Government Portal](https://ngp.e.gov.ph/) also describes itself as a single window for government content and online services, reinforcing the importance of centralized and organized access to official information.

The links above are reference portals. LingapPH does not replace official government agencies; users should always verify program details, requirements, and application procedures through the responsible agency's official website.

## Features

### Current Implementation

- Homepage and platform introduction
- About page
- Services page
- Government agencies page
- Tools page
- FAQ page
- Financial, medical, and educational assistance categories
- Search interface design
- Navigation menu
- Shared CSS stylesheet

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure and content |
| CSS3 | Styling and page layouts |
| Font Awesome | Interface icons and visual indicators |

## Project Structure

```text
LingapPH/
│
├── css/
│   └── style.css
│
├── pages/
│   ├── about.html
│   ├── faq.html
│   ├── government.html
│   ├── services.html
│   └── tools.html
│
├── index.html
│
└── README.md
```

### Directory and File Description

| File / Directory | Description |
|---|---|
| `css/` | Contains the project's stylesheets. |
| `css/style.css` | Shared stylesheet for website styling and layout. |
| `pages/` | Contains the individual website pages. |
| `pages/about.html` | About page introducing LingapPH. |
| `pages/faq.html` | FAQ page. |
| `pages/government.html` | Government agencies page. |
| `pages/services.html` | Services and assistance categories page. |
| `pages/tools.html` | Tools page. |
| `index.html` | Main homepage and website entry point. |
| `README.md` | Project documentation. |

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/lingapph.git
```

### 2. Navigate to the Project Directory

```bash
cd lingapph
```

### 3. Open the Website

Open `index.html` in your preferred web browser.

For local development, you can also use the Live Server extension in Visual Studio Code.

## Design System

LingapPH follows a minimal and clean visual direction, prioritizing readability, consistency, and ease of navigation.

### Color Palette

| Color | Hex Code | Usage |
|---|---|---|
| Navy | `#112F43` | Primary backgrounds |
| Blue | `#245B7D` | Buttons and accents |
| White | `#FFFFFF` | Main surfaces |
| Light Gray | `#F0F3F5` | Secondary backgrounds |
| Border Gray | `#D9E1E6` | Borders and dividers |
| Text | `#27323C` | Primary text |
| Muted Gray | `#71808E` | Supporting text |

### Typography

- Heading Font: Urbanist
- Body Font: Helvetica
- Fallback Fonts: Arial, sans-serif

## Project Status

**In Development**

LingapPH currently uses a static frontend implementation built with HTML and CSS. Search functionality, program listings, and other interactive features are not yet connected to a backend or live government data sources.

## Disclaimer

LingapPH is an information platform. It does not directly process government assistance applications, determine eligibility, approve benefits, or distribute financial assistance.

Users should verify program information, eligibility requirements, and application procedures through the appropriate official government agencies.

## Contributors

- Dores Bunquin
- Efrain Borbon
- John Elvin Endrenal
- Karl Mhigos Lopez

---

*Making public assistance information easier to discover and understand.*
