# GitHub Codespace for R Markdown/Notebook

**Launch the environment by clicking on the green Code button and creating codespace on main**
![Create/Launch Codespaces](images/codespace_create.png)

## Run R Markdown/Notebook

An example, `test.Rmd`, is ready to try.

**To render the test R Markdown into a PDF file, run the following line in R terminal**
```
rmarkdown::render("test.Rmd", output_format="pdf_document")
```

## Run R code in a Jupyter Notebook

Please try `notebook.ipynb`. But setup is required following the 9 steps below.

- Step 1:

From top right corner of the opened `notebook.ipynb` file pane.

![Select Kernel](images/select_kernel_1.png)

- Step 2:

![Select Kernel](images/select_kernel_2.png)

- Step 3:

![Select Kernel](images/select_kernel_3.png)

- Step 4:

![Select Kernel](images/select_kernel_4.png)

- Step 5: Select `base (Python x.x.x)`

![Select Kernel](images/select_kernel_5.png)

- Step 6: Click on the top right corner button again to select kernel.

![Select Kernel](images/select_kernel_6.png)

- Step 7: Choose `Select Another kernel...` 

![Select Kernel](images/select_kernel_7.png)

- Step 8: Choose `Jupyter Kernel...`

![Select Kernel](images/select_kernel_8.png)


- Step 9: Choose `R (base)`

![Select Kernel](images/select_kernel_9.png)

Now `R` should appear at the lower right corner of each code cell to indicate that each code cell is with `R` kernel, and each code cell is runable.

**To render a Jupyter Notebook with R code to a PDF file, click on the `...` and select `export`**
![Render](images/render_pdf.png)
