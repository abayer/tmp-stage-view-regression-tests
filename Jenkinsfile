stage "pass"
echo "I'm passing"

stage "also pass"
echo "look, also passing"

stage "and now fail but retry?"
retry(5) {
    error "FAIL BABY"
}