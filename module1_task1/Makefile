build:
	hugo -d module1_task0/dist/index.html

clean:
	rm -r dist/*

post:
	hugo new posts/$(POST_NAME).md
	echo 'title: "$(POST_TITLE)"' >> content/$(POST_NAME).md
