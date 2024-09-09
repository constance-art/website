---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="drawings" >}}
    design:
      columns: '1'
  - block: markdown
    content:
      title: How to Book a Pet Portrait
      text: <h2>1. Select a Photo</h2><p>To create the highest quality portrait, a high-resolution image is essential. You’re welcome to send several photos, and together, we can select the one that will work best.</p><p>&nbsp;</p><h2>2. Size and Price</h2><p>After we’ve finalized the photo, you’ll need to choose the size of your portrait. I offer several options:</p><table border="1" cellpadding="10" cellspacing="0"><thead><tr><th>Size</th><th>Single Portrait</th><th>Double Portrait</th></tr></thead><tbody><tr><td>24x30 cm</td><td>650 €</td><td>850 €</td></tr><tr><td>30x40 cm</td><td>750 €</td><td>950 €</td></tr></tbody></table><p>&nbsp;</p><h2>3. Payment</h2><p>Once I’ve completed your portrait, I will send you a photo of the result. After you confirm that you are happy with it, you can proceed with the payment.</p><p>Payments are processed via Paypal or bank transfer. Once the full payment is received, I will ship your portrait, and you’ll receive a tracking number to monitor the delivery. The prices include shipping fees.</p>
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Thank your for your interest. I am happy to hear from you!
      # Contact (add or remove contact options as necessary)
      email: info@constance-art.com
      phone: 
      address:
        street:
        city: Delft
        region:
        postcode: The Netherlands
        country:
        country_code:
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
