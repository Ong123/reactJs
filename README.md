<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />
    <title>React Js</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/react/0.13.3/react.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/react/0.13.3/JSXTransformer.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
</head>
<body>

    <div id="content"></div>

    <script type="text/jsx">
    
        var reactComponent = React.createClass({
            render: function() {
                return (
                        <h2>hello World</h2>
                );
            }
        });
        React.render(<reactComponent />, document.getElementById('content'));
    </script>

</body>
</html>
