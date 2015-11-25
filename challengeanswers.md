var x = 2;

Step 1 (math eval.): x = 7 - x;

x = 7 - 2 = 5;

Step 2 (conditional): if ( x > 8) { x = 2; } else { x = x + 7 };

x = 5 + 7 = 12;

Step 3 (for loop): for (var i=0; i<5; i++) { x = x + i };

loop 0: x = 12 + 0 = 12; loop 1: 12 + 1 = 13; loop 2: 13 + 2 = 15; loop 3: 15 + 3 = 18; loop 4: 18 + 4 = 22;

Step 4 (function): var x = x / 11; x = function addTwo(x) { x = x + 2; return x;};

x = 22 / 11 = 2; 
x = addTwo(2) = 2 + 2 = 4;

answer = 4.
