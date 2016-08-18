stage "pass"
echo "I'm passing"

stage "pass again"
sleep 10
echo "I'm passing and sleeping for 10 seconds"

stage "and now paralllllelllll"
parallel(["foo": {
                 echo "Foo's fine"
             },
          "bar": {
              sleep 10
              echo "Bar slept a bit"
          },
          "baz": {
              error "Baz hates you and everything to do with you."
          }])


