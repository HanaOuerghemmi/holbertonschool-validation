# Makefile for Go-Hugo website

# Build the website
build:
	@hugo

clean: # Clean up the build directory
	rm -rf dist/*

# Create a new blog post
post:
	hugo new posts/$(POST_NAME).md
	sed -i 's/title: .*/title: "$(POST_TITLE)"/' content/posts/$(POST_NAME).md

# Print usage for each target
# usage: make help
help:
	@echo "Usage:"
	cat Makefile | grep '##' | tr -d '##'
