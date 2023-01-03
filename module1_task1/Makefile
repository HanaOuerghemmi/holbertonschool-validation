# Makefile for Go-Hugo website

# Build the website
build:
	@hugo
# Clean up the build directory
clean:
	rm -rf dist/*

# Create a new blog post
post:
	hugo new posts/$(POST_NAME).md
	sed -i '2s/title: .*/title: "$(POST_TITLE)"/' content/posts/$(POST_NAME).md
