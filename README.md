# Huffman


# Huffman Tree Decode
	In this project the user enters an input file which we assume is Huffman coded  and a name for the output file.
	This program practicaly is to decode input file (name given by user) to an output (name given by user) with ASCII characters.


## Installation
You will need to have maven installed on your computer. In order to install maven execute the following if you use Ubuntu
```bash
sudo apt install maven
```
Check if the installation was correct by typing
```bash
mvn -version
```
## Usage

In order to compile the project, execute the following 
```bash
mvn compile
```
Create a jar using
```bash
mvn package
```
### Execution
Execute the program by typing
```bash
java -cp target/Assignment-1.0-SNAPSHOT.jar org.hua.assignment.Decode (your input file) (your output file)
```
WARNING! You will need to have encoded an input for this part to work. Create an encoded file by running part 4 like this:
```bash
java -cp target/Assignment-1.0-SNAPSHOT.jar org.hua.assignment.Encoed (your input file) (your output file)
```
