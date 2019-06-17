# accessibility-checklist
A short checklist of accessibility checks for pull requests, for government services.

To use this, copy and paste the following into a [Pull Request template](https://help.github.com/en/articles/creating-a-pull-request-template-for-your-repository).

## Essential checks

- [ ] Site is keyboard accessible - All interactions can be accessed with a keyboard

- [ ] Site is free of keyboard traps - the keyboard focus is never trapped in a loop

- [ ] All form inputs have explicit labels

- [ ] All relevant images use an img tag

- [ ] All images have alt attributes
    
- [ ] Multimedia has appropriate captioning and audio description

- [ ] Text has sufficient color contrast ( acontrast ratio of 4.5:1 with the background)

For the full list, see [18F's Accessibility Checklist](https://accessibility.18f.gov/checklist/).

All government services need to be compliant with [WCAG 2.1 to AA](https://www.w3.org/WAI/WCAG21/quickref/?currentsidebar=%23col_overview&levels=aaa). This checklist does not replace an external audit. You still need to test with users and assistive technologies. This checklist just helps you find major issues faster, so you can avoid building on top of them. The sooner you incorporate accessibility, the easier it is! 
