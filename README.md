# Ruby-Calc-Max-Word-Freq
Calculate maximum words frequency is an assignment from course 'Ruby on Rails Intro'
#Getting Started

* _Install the following gem._
    - gem install rspec
    - gem install rspec-its
* _Run the rspec command from the root directory to execute the unit tests within the spec directory. This command should be run from the root directory of the project._
    - rspec

* _calc_max_words_freq.rb contains two clasess
    - LineAnalyzer : Takes a line and a line number as input and calculate maximum number of occurrences for a single word and words with maximum number of occurrences.
    - Solution : Reads file 'test.txt' and store each line as an array of LineAnalyzer object by passing each line and and its line number. And calculate highest occurrences of words among all lines and filter such LineAnalyzers.
