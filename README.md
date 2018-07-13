# POJO-for-CSV
Tiny utility to generate Java POJO classes for Open CSV API. generate java classes from CSV header to parse.
# Generate Java pojo classes that can be used to read and write CSV data to bean and viseversa.

# Usage
Apache common lang and OpenCSV jars should be included in classpath

input CSV file should only include 1 row as a header to generate classes.
Add suffix- * in header name to generate required annotation field.

Just update method parameter of main method like CSV file path, Output folder where POJO classes will be generated, package name, class name.

Right click and run the project
