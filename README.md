let y = [1, 2, 3, 4];
        y.splice(0, 1, y.splice(1, 1, y[0])[0]);
        console.log(y);
