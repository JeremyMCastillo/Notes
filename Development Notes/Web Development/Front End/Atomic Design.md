[Source](https://bradfrost.com/blog/post/atomic-web-design/)
# Overview
Atomic Design is a methodology for creating design systems, there are five levels. 

# Hierarchy
## 1. Atoms
The base construction element for your designs. These are generally the raw HTML elements on their own. These could be form inputs, buttons, paragraph sections, but each entity is designed on their own. 

Reusing atoms in several molecules means you only have to design each base element once.

## 2. Molecules
When a few atoms are combined to form a functional entity, a molecule is formed. An example would be an input label, an input field, and a submit button. 

Reusing molecules in several organisms means that look and feel will be unified, and functionality will be universal across the entire application. 

## 3. Organisms
An organism denotes a distinct area of an application page. It uses multiple molecules to perform one high level job. For example, a website header would have a logo, menu, and possibly a search bar. Each of these three could be considered their own Molecule, making up a whole organism. 

Reusing organisms in multiple templates means you will do the minimum amount of work to implement the maximum number of pages. 

## 4. Templates
A template defines how multiple organisms come together to form a full page. It is at this stage that we can begin to decide the optimal configuration of organisms to serve the intended purpose of the page. Templates can define both placement and functionality of organisms. 

## 5. Pages
A page is the final implementation of a template. By constructing each page from the atom level up, it is possible to uniformly update page look and feel with minimum effort. 

[[Programming MOC]]