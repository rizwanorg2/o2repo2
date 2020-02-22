
@Library('legacy-shared-libraries@Test_PaC') _

import com.github.jenkins.pipelines.*

new LegacyPipeline(this,
[
	projectSpace: 'Legacy',
	jenkinsLabel: 'master',
	configType: 'java',
	buildDebugmode: 'off',
	unittestDebugmode: 'off',
	sonarqubeProject: 'github-lib',
    sonatypeIqApp: 'github-lib',
	domain: 'git'
]).execute()

