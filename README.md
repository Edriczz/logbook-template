# Internship Logbook Template

This is a LaTeX template designed for creating daily activity reports for internship programs. It is clean, professional, and easy to customize.

## Prerequisites

To use this template, you need a LaTeX distribution installed on your system.

-   **Compiler**: `xelatex` is required because this template uses the `fontspec` package to load system fonts.
-   **Fonts**: The **Poppins** font family must be installed on your system.
    -   You can download Poppins from [Google Fonts](https://fonts.google.com/specimen/Poppins).

## Usage

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/Edriczz/logbook-template.git
    cd logbook-template
    ```

2.  **Customize the Template**
    Open `main.tex` and update the following placeholders:
    -   **Company Logo**: Replace `PT_XXXXX_Tbk.png` with your company's logo file.
    -   **Company Name**: Replace "PT XXXXX Tbk." with the actual company name.
    -   **Identity Section**: Update Name, NIM, Institution, Internship Department, and Period data.
    -   **Log Entries**: Update the `longtable` rows with your actual daily activities.

3.  **Compile**
    Run the following command in your terminal:
    ```bash
    xelatex main.tex
    ```
    This will generate `main.pdf`.

## File Structure

-   `main.tex`: The main LaTeX source file.
-   `PT_XXXXX_Tbk.png`: Placeholder image for the company logo.
-   `.gitignore`: Specifies files to be ignored by Git (auxiliary LaTeX files).

## License

Feel free to use and modify this template for your personal use.
