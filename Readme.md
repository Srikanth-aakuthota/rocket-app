# Create the README.md file
echo "# Rocket App

This is a simple web application built using the Rocket framework in Rust. The application demonstrates a basic setup with a single route that returns a \"Hello, world!\" message.

## Project Structure

- \`Cargo.toml\`: Contains the project metadata and dependencies.
- \`src/main.rs\`: The main source file containing the Rocket application code.

## Dependencies

- \`rocket\`: A web framework for Rust.
- \`tokio\`: An asynchronous runtime for Rust.

## Getting Started

To run the application, follow these steps:

1. Ensure you have Rust installed. If not, install it from [rust-lang.org](https://www.rust-lang.org/).
2. Clone the repository:
   \`\`\`sh
   git clone https://github.com/Srikanth-aakuthota/rocket-app.git
   \`\`\`
3. Navigate to the project directory:
   \`\`\`sh
   cd rocket-app
   \`\`\`
4. Build and run the application:
   \`\`\`sh
   cargo run
   \`\`\`

## Usage

Once the application is running, you can access it in your web browser at \`http://localhost:8000\`. You should see the message \"Hello, world!\".

## License

This project is licensed under the MIT License." > README.md

# Add the README.md file to the staging area
git add README.md

# Commit the changes
git commit -m "Add README.md with project description"

# Push the changes to the remote repository
git push origin master