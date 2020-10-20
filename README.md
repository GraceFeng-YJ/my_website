# my_website

install.packages("blogdown")

library(blogdown)

install_hugo()

blogdown::update_hugo()

blogdown::new_site(theme = "MarcusVirg/forty",
          theme_example = TRUE,
          empty_dirs = TRUE,
          to_yaml = TRUE)




