# HBR-Style Visualization

A Claude Code skill for creating sophisticated, editorial-style data visualizations and infographics in the signature style of the Harvard Business Review.

## Overview

This skill enables the creation of high-impact, professional visualizations that emulate the distinct editorial and academic aesthetic of the Harvard Business Review. The focus is on intellectual density, strategic clarity, and a sophisticated design that balances complex information with clean, readable layouts.

## Features

- **HBR Signature Aesthetic**: Crimson red accent color (`#A6192E`), slab serif typography, and clean layouts
- **Strategic Framing**: Every visualization built around a central argument or insight
- **Multiple Visualization Types**: 
  - Central Conceptual Frameworks (flywheels, maturity models)
  - Annotated Charts with Sidebars
  - 2x2 Strategic Matrices
- **Prompt Engineering Templates**: Ready-to-use templates for common visualization needs
- **Quality Checklist**: Ensure every visualization meets HBR standards

## Installation

### Claude Code

1. **Clone this repository:**
   ```bash
   git clone https://github.com/kgraph57/hbr-style-visualization.git
   ```

2. **Copy to your skills directory:**
   
   For personal skills (available across all projects):
   ```bash
   cp -r hbr-style-visualization ~/.claude/skills/
   ```
   
   For project-specific skills:
   ```bash
   cp -r hbr-style-visualization .claude/skills/
   ```

3. **Use the skill:**
   - Invoke directly: `/hbr-style-visualization`
   - Or let Claude load it automatically when you ask for HBR-style visualizations

### Claude.ai

Upload the `SKILL.md` file directly through the Claude.ai skills interface.

### Claude API

Use this skill via the Claude API by following the [Skills API documentation](https://platform.claude.com/docs/en/build-with-claude/skills-guide).

## Usage Examples

### Example 1: Create a Flywheel Diagram

```
Create a 4-step flywheel diagram illustrating the "Data Network Effect" in GenAI. 
The steps are: 1. Product Adoption, 2. Data Generation, 3. Model Improvement, 
4. Enhanced Value Proposition. Use a bold, circular arrow flow. The style should 
be academic and clean, like a Harvard Business Review infographic. Use HBR's 
crimson red for the arrows.
```

### Example 2: Annotated Chart with Sidebar

```
Generate a horizontal bar chart comparing "Time to Master" for different GenAI 
video models. Data: Seedance (4 weeks), Kling (6 weeks), Veo (5 weeks), Luma 
(2 weeks). Highlight Luma's bar in HBR crimson red. To the right, add a sidebar 
titled "Managerial Implications" with bullet points explaining that faster 
onboarding is a key competitive advantage. Use a sophisticated, HBR-style 
editorial layout.
```

### Example 3: 2x2 Strategic Matrix

```
Create a 2x2 matrix for the GenAI video market. X-axis: "Technical Capability 
(Low to High)". Y-axis: "Ecosystem & Usability (Low to High)". Position four 
players: Seedance 2.0 (High Tech, Mid Eco), Kling (Mid Tech, Mid Eco), Veo 
(High Tech, Low Eco), Luma (Mid Tech, High Eco). The design should be academic 
and minimalist, in the style of Harvard Business Review.
```

## Design Principles

### Color Palette
- **Background**: Light Cream `#FDFBF7` or Pure White `#FFFFFF`
- **Primary Text**: Charcoal Grey `#333333`
- **Primary Accent**: HBR Signature Crimson Red `#A6192E`
- **Secondary Accents**: Medium Grey `#666666`, Light Grey `#D9D9D9`

### Typography
- **Titles & Headlines**: Slab Serif (Rockwell, Roboto Slab, Zilla Slab)
- **Body Text**: Classic Serif (Garamond, Caslon, Libre Baskerville)
- **Data Labels**: Sans-Serif (Helvetica, Arial, Inter)

### Layout Standards
- Landscape orientation (16:9 or 3:2 aspect ratios)
- Generous whitespace for calm authority
- Bold lines for frameworks
- Sidebars for key takeaways and implications

## When to Use

Use this skill when:
- Developing presentations for academic or executive audiences
- Creating figures for research papers or business articles
- Designing strategic frameworks and conceptual models
- Visualizing data for managerial reports
- Communicating complex business insights with an authoritative, editorial tone

## References

- Harvard Business Review Style Guide
- "Good Charts: The HBR Guide to Making Smarter, More Persuasive Data Visualizations" by Scott Berinato

## License

This skill is provided as-is for educational and demonstration purposes.

## Author

Created by KEN

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.
