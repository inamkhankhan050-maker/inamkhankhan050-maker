# Website QA and launch checklist

Record the date, build or commit checked, browser/device, and outcome. Mark an item N/A with a reason when it does not apply.

## Content and behavior
- [ ] Confirm approved text, prices, contact details, and service area.
- [ ] Test navigation, calls to action, forms, search, and key user paths.
- [ ] Confirm form success and error messages; verify submissions reach the intended recipient.
- [ ] Confirm external links open the intended destination.
- [ ] Check empty, invalid, slow, and unavailable states where applicable.

## Layout and accessibility
- [ ] Review at a narrow mobile width, tablet width, and desktop width.
- [ ] Check for horizontal overflow, clipped text, and overlapping controls.
- [ ] Navigate with keyboard only; confirm visible focus and sensible tab order.
- [ ] Check heading order, labels, alternative text, and link purpose.
- [ ] Check text contrast and reduced-motion behavior.
- [ ] Confirm touch targets and fixed elements do not obstruct content.

## Technical
- [ ] Build, lint, and automated checks pass (or record the reason they are unavailable).
- [ ] Browser console has no new errors.
- [ ] Images load, have useful alternative text where needed, and use reasonable dimensions.
- [ ] Page title, description, canonical URL, and social preview metadata are correct.
- [ ] No secrets or private client data are included in the repository or built output.
- [ ] Redirects, 404 behavior, robots, and sitemap are appropriate to the project.
- [ ] Verify any analytics, map, form, or other third-party integration and its privacy behavior.

## Launch
- [ ] Confirm domain, DNS, TLS, hosting account owner, and rollback plan.
- [ ] Confirm client approval to publish.
- [ ] Deploy the reviewed build.
- [ ] Smoke-test the public URL on mobile and desktop.
- [ ] Check key links and user flows on the deployed site.
- [ ] Share the deployed URL and handover notes with the client.
