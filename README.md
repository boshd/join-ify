# Join-ify
### Shopify Data Engineering Challenge - Summer 2018

Join-ify is a simple joiner built with Python, with Pandas at it's core. Throw any two json files at it and it'll take care of the rest.

### Install
🔥 up your terminal and follow the instructions below.

Make sure pandas is installed. If it isn't, just run
> pip install pandas

or check out the [pandas documentation](https://pandas.pydata.org/getpandas.html) for more info.

Next, run
> git clone https://github.com/Kareemarab/Join-ify.git

and access the directory
> cd join-ify

Create a virtual environemnt in your directory, **if _needed_** by running
> source venv/bin/activate

and finally, change the joiner file's permission by running
> chmod +x joiner

That's it, you're all set!

### Usage
> $ ./joiner {join type (inner/left/right/outer)} {left table (json file)} {right table (json file)} {key from left table} {key from right table}

Example:
> $ ./joiner inner customers.json orders.json cid customer_id



