---
layout: page
icon: fas fa-envelope
order: 5
title: Contact
---

<style>
.page-contact .contact-form { max-width: 600px; margin: 2rem 0; }
.page-contact .form-group { margin-bottom: 1.75rem; }
.page-contact .form-group label { display: block; margin-bottom: 0.5rem; font-weight: 600; color: var(--heading-color); }
.page-contact .form-group input,
.page-contact .form-group select,
.page-contact .form-group textarea { width: 100%; padding: 0.85rem 1rem; border: 2px solid #e9ecef; border-radius: 6px; background: var(--main-bg); color: var(--text-color); font-size: 1rem; transition: all 0.2s ease; }
[data-mode="dark"] .page-contact .form-group input,
[data-mode="dark"] .page-contact .form-group select,
[data-mode="dark"] .page-contact .form-group textarea { border-color: #3d444d; }
.page-contact .form-group input:focus,
.page-contact .form-group select:focus,
.page-contact .form-group textarea:focus { outline: none; border-color: #2a7ae2; box-shadow: 0 0 0 3px rgba(42, 122, 226, 0.1); }
.page-contact .form-group select { appearance: none; background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12'%3E%3Cpath fill='%23666' d='M6 9L1 4h10z'/%3E%3C/svg%3E"); background-repeat: no-repeat; background-position: right 1rem center; padding-right: 2.5rem; cursor: pointer; }
[data-mode="dark"] .page-contact .form-group select { background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12'%3E%3Cpath fill='%23aaa' d='M6 9L1 4h10z'/%3E%3C/svg%3E"); }
.page-contact .form-group textarea { resize: vertical; min-height: 140px; }
.page-contact .contact-form button[type="submit"] { background: #2a7ae2; color: #ffffff !important; padding: 0.85rem 2.5rem; border: none; border-radius: 6px; font-size: 1rem; font-weight: 600; cursor: pointer; transition: all 0.2s ease; margin-top: 0.5rem; }
.page-contact .contact-form button[type="submit"]:hover { background: #1e6fd6; transform: translateY(-1px); box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15); }
@media (max-width: 768px) { .page-contact .contact-form button[type="submit"] { width: 100%; } }
</style>

## Let's Talk Design

Whether you have questions about templates, need custom design work, or want to discuss a project—I'm here to help.

<div class="page-contact">
  <form action="https://formspree.io/f/mgvnkjer" method="POST" class="contact-form">
    <div class="form-group">
      <label for="name">Name <span class="required">*</span></label>
      <input 
        type="text" 
        name="name" 
        id="name" 
        required 
        placeholder="John Doe"
        autocomplete="name"
      >
    </div>

    <div class="form-group">
      <label for="email">Email <span class="required">*</span></label>
      <input 
        type="email" 
        name="email" 
        id="email" 
        required 
        placeholder="john@example.com"
        autocomplete="email"
      >
    </div>

    <div class="form-group">
      <label for="project-type">What brings you here? <span class="required">*</span></label>
      <select name="project-type" id="project-type" required>
        <option value="">Select one...</option>
        <option value="Template Question">Question about a template</option>
        <option value="Template Support">Template support/technical issue</option>
        <option value="Custom Healthcare">Custom healthcare design</option>
        <option value="Custom Coffee">Custom coffee brand work</option>
        <option value="UI Kit">UI/component system project</option>
        <option value="Bulk License">Bulk/team licensing inquiry</option>
        <option value="Partnership">Collaboration opportunity</option>
        <option value="Other">Something else</option>
      </select>
    </div>

    <div class="form-group">
      <label for="message">Message <span class="required">*</span></label>
      <textarea 
        name="message" 
        id="message" 
        rows="8" 
        required 
        placeholder="Tell me about your project or question..."
      ></textarea>
      <small style="display: block; margin-top: 0.5rem; color: var(--text-muted); font-size: 0.875rem;">
        For template questions: Include template name and where purchased<br>
        For custom projects: Brief description, timeline, and budget range (if applicable)
      </small>
    </div>

    <!-- Honeypot for spam protection -->
    <input type="text" name="_gotcha" style="display:none" tabindex="-1" autocomplete="off">
    
    <!-- Hidden fields for better email organization -->
    <input type="hidden" name="_subject" value="New mkhub.dev contact form submission">
    
    <input type="hidden" name="_next" value="https://mkhub.dev/thanks">

    <button type="submit" class="btn">Send Message</button>
  </form>
</div>
---

## Direct Email

Prefer email? Reach me at **[matt@mkhub.dev](mailto:matt@mkhub.dev)**

**Typical response time:** 24-48 hours on weekdays

---

## What to Include in Your Message

### For Template Questions
- **Template name** and where you purchased it
- **Specific question** or issue you're encountering
- **File format** you're working with (Canva, Figma, etc.)
- **Screenshots** if relevant (attach via email if needed)

### For Custom Project Inquiries
- **Brief project description** - What you're looking to create
- **Timeline** - When you need it completed (if applicable)
- **Budget range** - Helps me provide accurate quotes
- **Examples or inspiration** - Links to styles or designs you like
- **Target audience** - Who will use/see this design

### For Technical Support
- **Purchase platform** (Etsy, Creative Market, Gumroad)
- **Order number or receipt** (helps verify purchase)
- **Specific issue** - What's not working as expected
- **Software version** - Canva, Figma version, etc.

---

## Custom Design Services

I take on select custom projects for:

### Healthcare Branding
- Medical practice identity systems
- Clinical documentation templates
- Healthcare app UI design
- Professional portfolio development

**Starting at:** $1,500 (complete brand identity)

### Coffee Business Design
- Roastery brand identity
- Packaging and label design
- Menu boards and signage
- Social media template systems

**Starting at:** $750 (packaging design) | $2,000 (full brand)

### Developer Resources
- Custom UI component libraries
- Design system creation
- Figma-to-code collaboration
- Technical documentation design

**Starting at:** $1,500 (component library) | $3,000 (complete system)

### Typical Timeline
**3-4 weeks** from kickoff to final delivery

[Learn more about custom work →](/portfolio/)

---

## Template Licensing

Need templates for your team?

### Bulk/Team Licensing Available
- Extended licenses for multiple users
- Volume discounts (5+ seats)
- Custom template packages
- Ongoing design support options

**Contact for quote** - Include team size and template needs

---

## Collaboration & Partnerships

Open to:
- **Affiliate partnerships** - Promote templates to your audience
- **Bundle collaborations** - Co-create template collections
- **Guest content** - Design tutorials and resources
- **Tool integrations** - Design systems for SaaS products

**Let's discuss** if you have an interesting collaboration idea.

---

## Connect Elsewhere

- **GitHub:** [github.com/m-kk](https://github.com/m-kk) - Open source design resources
- **Twitter/X:** [@mattkaili](https://twitter.com/mattkaili) - Design tips and updates
- **LinkedIn:** [linkedin.com/in/matt-kaili](https://www.linkedin.com/in/matt-kaili) - Professional network

---

## Response Time & Availability

**Current status:** Open for projects  
**Response time:** Within 24-48 hours (weekdays)  
**Time zone:** Central Time (US)

**Note:** If you don't hear back within 48 hours, please check your spam folder or send a follow-up email.

---

## Before You Go

### Quick Links
- [Browse portfolio →](/portfolio/)
- [Read recent posts →](/)
- [Learn about me →](/about/)

### FAQs

**Q: Do you offer refunds on templates?**  
A: Digital products are generally non-refundable, but I'll work with you to resolve any issues. Contact me if you're having problems.

**Q: Can I get a template customized?**  
A: Yes! Custom modifications start at $50-150 depending on complexity. Describe what you need in the form.

**Q: How long does custom design take?**  
A: Typically 3-4 weeks from kickoff to delivery. Rush projects available for +25% fee.

**Q: Do you offer payment plans?**  
A: For projects $1,000+, yes. 50% upfront, 50% on delivery.

**Q: What file formats do you deliver?**  
A: Depends on the project. Common formats: Figma, Canva, PDF, AI, SVG, PNG. Specified in project scope.

---

Looking forward to hearing about your project!

— Matt
