from flask import Flask, request, render_template, redirect, json
app = Flask(__name__)
file = open('cit.txt', 'r', encoding='utf-8')
spi = json.loads(file.read())
file.close()
@app.route('/')
def index():
    global spi
    page = render_template('main.html', a=spi)
    return page
@app.route('/create', methods=['GET'])
def create_html():
    page = render_template('create.html')
    return page

@app.route('/create', methods=['POST'])
def create():
    global spi
    spi[request.form.get("author")] = request.form.get("cit")
    spi = json.dumps(spi)
    file = open('cit.txt', 'w', encoding='utf-8')
    file.write(spi)
    file.close()
    spi = json.loads(spi)
    return redirect('/')

app.run(debug=True, port=8089)
