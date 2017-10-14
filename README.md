# Piel Canela

The Official Piel Canela Massage Therapy website.

![Piel Canela Massage Therapy](https://github.com/toddcf/pielcanela/blob/master/assets/img/hands-large.jpg "Piel Canela Massage Therapy")

## Technologies Used

- HTML5.
- CSS3.
- Bootstrap 4 Beta.
- JavaScript.
- jQuery.

## Current Iteration:

### All

1. Buttons: Make sure text never extends outside of the buttons as screen width shrinks (especially in SERVICES section).
2. Add social links to footer of each section.
3. Optional: Add and position all up and down chevrons.
4. Make POLICIES a modal.
5. Make H1s for each section responsive -- the text should get smaller as the screen width shrinks instead of being cut off.
6. Remove heading tags from all buttons, as their automatic padding is screwing up the vertical alignment.

### Hero (Header)

1. Replace bg image with a video (once we have the video).
2. Mobile Responsiveness:
  a. Position buttons correctly for different screen sizes.
3. I removed the white margin on top of HERO by manually adding `margin-top: -30px;`, but I shouldn't have to do that. Figure out what is wrong.

### Nav

1. Add hover effects to svg (if possible) and text below the logo, so users know it's a link.
2. Connect all links to other pages (once those pages are created).

### About the Therapist

N/A

### Benefits of Massage

1. Content: Overcome objections.
2. Content: Why Brenda is the best massage therapist for them.

### Testimonials

N/A

### Services and Rates

1. Center all SCHEDULE NOW and LEARN MORE buttons on each card.
   1. Also, remove the border that appears when you click on a button.
   2. Should INFANT MASSAGE's "Learn More" open a modal or a separate page?
2. GROUPS:
  1. Make POLICIES link stand out even when not hovering.
3. Test flexbox at all screen sizes.
4. Payments:
  1. Center each payment icon inside its column div. (Accomplishing this should make their spacing look right at all screen widths.)
  2. animate.css each payment logo, one after another.

### Schedule Now / Contact / Client Forms

1. Fix hover effect on phone number. (Don't turn blue when hovering. Always underline so people know it can be clicked.)
2. Email Form:
  1. Add labels, but maybe don't display them. (For ADA purposes only.)
  2. Improve the styling.
  3. Link to actual email system and test it. (Must deploy in order to test.)
3. Add card with link to client forms with separate PDF pages -- and center the button within its column.

### Footer

- N/A

### FAQ Page

1. Plain English.
2. Use Bootstrap 4's expand and hide features. (And automatically close one answer when a different question is clicked.)

### Gift Certificates Page

1. Use a lightbox to display images of the gift certificates (front and back) when clicked.

### Policies (Modal AND Separate Page)
  
- Cancellation Policy
- 24-Hour Advance Notice
- No-Shows
- Late Arrivals
- Massage Certifications
- Insurance
- Links to client forms as separate PDF pages.
- ADD: PRICES SUBJECT TO CHANGE.
- ADD: TRIP CHARGE INFO.

## Final Checks

1. Make sure the following are visible against all their various backgrounds:
  1. Chevrons
  2. Nav Icon
  3. Piel Canela Massage Therapy Logo
  4. Social Media Icons
2. Test mobile responsiveness.

## Deployment

1. Test deploy to Heroku.
2. Get confirmation from Brenda.
3. Deploy to GoDaddy.
4. Have GoDaddy link the old URL to the new URL (instead of the other way around, like it is now).

## Future Iterations:

1. Set active class on nav to whichever section you're viewing.
2. Create MailChimp list and add signup form (and icon) to this website.