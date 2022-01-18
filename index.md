#Relative and Absolute References

## **What are they?**

<p>
According to Microsoft Excel support, Relative and Absolute References refer to cell referencing and how it refers to the cells around it. Relative reference refers to another cell based on its location relative to the cell that’s referencing it. For example, if the A1 cell referenced data in the B1 cell, for ex: =B1+1, the program would be referring to a cell one column to the right. If the formula in cell A1 were then copied to cell A10 the new formula would be =B10+1 because B10 is one cell to the right of the cell doing the referring.
  </p>
  <p>
	Absolute referencing unlike relative does not consider where the cell doing the referencing is. To use the above example if the formula in cell A1 was =B1+1 and it was moved into cell A10 it would still be =B1+1. The final type of referencing is a mixed reference that as you would expect is a combination of the two. This reference makes either the row or column absolute and the other relative. 
 </p>
  
## **Why are they used?**

<p>
	A user would find these referencing types useful as they provide the ability to quickly reproduce the same calculation multiple times with different variables. For example, if a teacher had a grade sheet for a class of 10 that included 10 assignments for each student and the teacher wanted the final grade for each student, they could write a formula for the first student using the relative reference of that first students 10 assignments and determine that student’s grade. The teacher could then reuse that formula by changing the relative references and it would be able to calculate all the other students’ final grades with very little extra time. 
</p>
<p>
	If this same teacher decided to add a curve to the final grade for all the students that teacher could use absolute referencing to refer to a single cell that holds the curve value and use that in each final grade calculation for each student.
</p>
	
	
## **How are they used?**

<p>
	The way to tell excel how to treat these three reference types differently is the use of the dollar sign to denote the use of absolute referencing. The dollar sign would precede any cell reference component that would be absolute or fixed.  
	</p>
	<p>
	Relative Referencing		=B1+1
	</p>
	<p>
	Absolute Referencing		=$B$1+1
	</p>
	<p>
	Mixed Referencing		=B$1+1
	</p>
	
## **Examples with data.**

<p>
	
	</p>
	
## **References:**

<p>
	“Microsoft.” _Microsoft Support_, https://support.microsoft.com/en-us/office/switch-between-relative-absolute-and-mixed-references-dfec08cd-ae65-4f56-839e-5f0d8d0baca9. 
	</p>


You can use the [editor on GitHub](https://github.com/ngchampion/AdvancedDataScience/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ngchampion/AdvancedDataScience/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
