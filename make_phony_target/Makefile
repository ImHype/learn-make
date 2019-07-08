.PHONY: build
.PHONY: clean

# If your dir has an file which called `build`. Then your output for the `make build` will be like above:：
# make: `build' is up to date.

# So we need make the target - `build` to be an phony target, by `.PHONY: build`

build:
	make clean && make a.txt

clean: 
	rm -rf *.txt

a.txt: b.txt c.txt
	cat b.txt c.txt > a.txt

b.txt:
	echo "hello" > b.txt

c.txt:
	echo "world" > c.txt
