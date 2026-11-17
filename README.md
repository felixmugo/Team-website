# Team Name: Lab 2 FELIX

**Live site:** https://felixmugo.github.io/team-website/

## Team
| Name | Registration no. | GitHub username |
|------|------------------|-----------------|
|   Felix Mugo   |     COM/3495/26             | felixmugo                |
|      |                  |                 |

## Who drove each part
- Part 0, 1, 2, 3, 4: Felix Mugo


## Personalisation
- Our colours: Light theme: #155E75 and #134E4A. Dark theme: #7DD3FC and #A7F3D0.
- Projects we added: Personal GitHub repository and Portfolio website.
- Extension challenge(s) completed:  Added a new Git category, updated the categoryNames object, added a Git filter button, and customised the primary colours for both themes while considering accessibility and text contrast.

## Reflection

1. A button supports keyboard interaction using Enter and Space, while a clickable div does not. Buttons also have built-in accessibility features that screen readers recognise. Without these features, keyboard users and visually impaired users would be affected.

2. Without defer, the browser would execute JavaScript before finishing to parse the HTML. Some elements might not yet exist, causing document.querySelector() to return null. This could break features such as navigation, project rendering and the contact form.

3. Using innerHTML with visitor-provided titles could allow malicious HTML or JavaScript to be inserted into the webpage. This could cause cross-site scripting (XSS) attacks. Using textContent displays the input as plain text and helps prevent this security risk.

4. JavaScript validation can be bypassed by disabling JavaScript or modifying requests. Server-side validation is necessary because the server cannot trust data received from the browser. It protects the website from invalid or malicious input.

5. An origin consists of a protocol, domain and port. Double-clicked files and Live Server use different origins, so their localStorage data is stored separately. Therefore, the saved theme preference does not automatically transfer between them.

6. The navigation bar and footer are duplicated across our HTML pages. This makes maintenance difficult because changes must be made on every page, which can cause inconsistencies. We could avoid this by using reusable components or shared HTML templates.

