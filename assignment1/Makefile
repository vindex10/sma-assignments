.PHONY: export

export: stk9900-ananiev.assignment-1.pdf

stk9900-ananiev.assignment-1.pdf: assignment-1.ipynb
	jupyter nbconvert --to=pdf --output=$@ $<
