//<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>module4-solution</title>
</head>
<body>
    <script>
        let names = ['John', 'Jane', 'Jim', 'Alice', 'Bob', 'Jill'];

for (let i = 0; i < names.length; i++) {
  if (names[i][0].toLowerCase() === 'j') {
    console.log('Goodbye ' + names[i]);
  } else {
    console.log('Hello ' + names[i]);
  }
}
    </script>
</body>
</html>
