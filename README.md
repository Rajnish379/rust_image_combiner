cargo run -- image/a1.png image/a2.png image/output.png 
First two arguments gives the paths of the images to the compiler
The last argument is the path where the output image needs to be created

cargo new combiner 
The above line will initialize an empty rust project for you

image = "0.23.14"
This line in the Cargo.toml file will add the image crate to your respective rust project when you run it using cargo run command