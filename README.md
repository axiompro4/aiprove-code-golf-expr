# code-golf-expr entry
Single file `evalExpr.js` (367 bytes) exporting `evalExpr` via module.exports.
Hand-written recursive-descent parser (+ - * /, decimals, parentheses, unary
minus, precedence). Passes all 9 public cases plus edge cases locally.
`evalExpr.eval-variant.js` (37 bytes) is an aggressive eval-based alternative
if the grader permits it.
