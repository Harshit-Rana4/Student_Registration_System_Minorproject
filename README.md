# Student Registration System with Dynamic HTML Table

A beginner-friendly, lightweight web application built using **Python Flask** inside a Jupyter Notebook environment. This mini-project meets all foundational criteria for a beginner web application framework, showcasing clean route management, robust data binding, server-side data collection, form validation, and simple dynamic HTML UI layouts.

---

## 🛠️ Minimum Project Compliance Checklist

*   **Single File Configuration**: Ready to execute in local notebook execution runtimes.
*   **Three Active Routes**: 
    *   `GET /` - Renders the structural data intake form.
    *   `POST /register` - Performs server-side sanity validation and updates storage tables.
    *   `GET /about` - Supplies runtime metadata metrics.
*   **Data Validation Checkpoint**: Rejects incomplete attributes or invalid email layout patterns with clear user feedback banners.
*   **Dynamic Data Table Component**: Displays interactive structured arrays mapping out every single successful session enrollment instance.

---

## 📂 Project Architecture

For notebook tracking, templates are loaded inline as string variables:
```text
student_registration_table.ipynb  <-- Contains application logic and UI strings
```

---

## 🚀 Execution Instructions

1. **Initialize Requirements**
   Open your Jupyter kernel environment or shell prompt, and confirm you have Flask installed:
   ```bash
   pip install flask
   ```

2. **Execute the Workspace Cells**
   * Open the `.ipynb` file in your notebook editor (JupyterLab, VS Code, or Classic Notebook).
   * Run the application workspace block.

3. **Interact with the Web Application**
   * The local server will boot on your host loops automatically.
   * Access the application by navigating to: **`http://127.0.0.1:5000/`**
   * Fill in test registration fields to dynamically generate items inside the confirmation data framework.

---

## 📋 Test Vectors Configuration

To evaluate data framework reliability, verify the following inputs:
*   **Valid Enrollment**: Input full details to render the record in the HTML data table layout.
*   **Empty Attributes**: Submit a completely blank structural entry to trigger the mandatory element exception banners.
*   **Incorrect Format Checks**: Input a standard name but use a missing domain string format (e.g., `invalidemail`) to confirm validation catches it.
