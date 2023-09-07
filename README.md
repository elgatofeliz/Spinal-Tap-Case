# Spinal-Tap-Case
    FreeCodeCamp
    JavaScript Algorithms and Data Structures
    Intermediate Algorithm Scripting

Spinal Tap Case

Convert a string to spinal case. Spinal case is all-lowercase-words-joined-by-dashes.

--- Here's the Code ---

function spinalCase(str) {
  return str.split(/\s|_|(?=[A-Z])/).join("-").toLowerCase();
}

spinalCase('This Is Spinal Tap');
