##What does a feature file look like?

<pre><code data-trim>

Feature: Jira integration
    In order to facilitate the authoring of Behat features by non-developers
    As a developer
    I want to write an extension to load features from Jira issues.

Scenario: Load Me!
    Given I am a Jira issue
    And I contain a Behat feature
    When I am loaded by JiraExtension
    Then I should parsed by Gherkin

</code></pre>

Can write in **any** language. Even **Pirate**

<pre><code data-trim>
Ahoy matey!: Jira integration
    In order to facilitate the authoring of Behat features by non-developers
    As a developer
    I want to write an extension to load features from Jira issues.

Heave to:  Load Me!
    Gangway! I am a Jira issue
    Aye I contain a Behat feature
    Blimey! I am loaded by JiraExtension
    Let go and haul I should parsed by Gherkin
</code></pre>