# ACTIVITY-3_Hydie_Act2c

<?php

$grade = 85; 

if ($grade >= 90 && $grade <= 100) {
    $letter = "A";
    $status = "PASS";
} elseif ($grade >= 80 && $grade <= 89) {
    $letter = "B";
    $status = "PASS";
} elseif ($grade >= 70 && $grade <= 79) {
    $letter = "C";
    $status = "PASS";
} elseif ($grade >= 60 && $grade <= 69) {
    $letter = "D";
    $status = "FAILED";
} elseif ($grade >= 0 && $grade <= 59) {
    $letter = "F";
    $status = "FAILED";
} else {
    $letter = "Invalid";
    $status = "Invalid Grade";
}

echo "Grade: " . $grade . "<br>";
echo "Letter Grade: " . $letter . "<br>";
echo "Result: " . $status;

?>
