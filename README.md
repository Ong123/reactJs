<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />
    <title>ReactJs</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/react/0.13.3/react.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/react/0.13.3/JSXTransformer.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
</head>
<body>

    <div id="content"></div>

    <script type="text/jsx">
    
        var OngComponent = React.createClass({
            render: function() {
                return (
                        <h2>hello world</h2>
                );
            }
        });
        React.render(<OngComponent />, document.getElementById('content'));
    </script>

</body>
</html>
