pipelineJob('job-dsl-plugin') {
  definition {
    cpsScm {
      scm {
        git {
          remote {
            url('https://github.com/bhanukumari/jenlkins-role.git')
          }
          branch('*/main')
        }
      }
      lightweight()
    }
  }
}
