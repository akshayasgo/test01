def agents = ['dev', 'test', 'dev', 'test']

node('dev') {
    for (agentLabel in agents) {
        node(agentLabel) {
            stage('Stage') {
                echo "Running on agent: $agentLabel, hello"
            }
        }
    }
}
