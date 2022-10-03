# Dmoney API JMETER Project

## Test Scenario
This is a Jmeter Project where the DmoneyAPI is tested by creating test cases for several API request. The ramp-up and the number of threads in jmeter setting were kept as 1.

## Operations:
1. **Login** 
2. **Creating users** 
3. **Searching users** 
4. **Update** (*Patch* and *PUT*)
5.  **Delete**

## Pre-requisite
1. Install jdk 8 or any LTS version
2. Download and extract Apache Jmeter 5.5 or any latest version
3. Configure JAVA_HOME and JMETER_HOME in system environment variable

## To Run This Project
1. Clone this project or download the .jmx file in the project directory.
2. You can generate your own HTML summary report by running the following code in the terminal:
```ruby
jmeter -n -t DmoneyAPI.jmx -l DmoneyAPI.csv -e -o Reports
```

### HTML Summary Report
![Screenshot_4](https://user-images.githubusercontent.com/40294642/193668222-3ddaeb3d-66aa-4cc8-977e-c8454df1060a.png)
![Screenshot_5](https://user-images.githubusercontent.com/40294642/193668229-c71808a6-d685-436f-9251-18f55840ce0f.png)

### Whole project structure in Jmeter
![1](https://user-images.githubusercontent.com/40294642/193669801-ec0b6a7b-3217-42c3-bb12-d20dc1336da4.png)

### Results from 'View Results Tree'
![2](https://user-images.githubusercontent.com/40294642/193670107-4382e7af-c111-44b0-8022-03fe8c5835b3.png)

### Jmeter Summary Report
![3](https://user-images.githubusercontent.com/40294642/193670626-5833d0c9-2e4b-4bad-ab98-a67e72d99162.png)
