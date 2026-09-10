(require 'clojure.test
         'tsuchifumi.methods.test-ontology
         'tsuchifumi.methods.test-analyze
         'tsuchifumi.methods.test-sysdyn
         'tsuchifumi.methods.test-risk
         'tsuchifumi.methods.test-coscientist
         'tsuchifumi.methods.test-social
         'tsuchifumi.methods.test-kotoba
         'tsuchifumi.methods.test-autorun
         'tsuchifumi.methods.test-viz)

(let [result (apply clojure.test/run-tests
                    '[tsuchifumi.methods.test-ontology
                      tsuchifumi.methods.test-analyze
                      tsuchifumi.methods.test-sysdyn
                      tsuchifumi.methods.test-risk
                      tsuchifumi.methods.test-coscientist
                      tsuchifumi.methods.test-social
                      tsuchifumi.methods.test-kotoba
                      tsuchifumi.methods.test-autorun
                      tsuchifumi.methods.test-viz])]
  (when-not (zero? (+ (:fail result) (:error result)))
    (throw (ex-info "tsuchifumi tests failed" result))))
