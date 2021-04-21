---
title: Setting up an OSF Data Component
teaching: 2
exercises: 13
questions: []
objectives:
  - Have an OSF project component ready to house the data
keypoints:
  - We use the _test_ subdomain of the OSF because we're testing things
  - Make a note of the data component's id - we'll need that later!
day: 1
order: 400000
missingDependencies: []
dependencies:
  - /fig/osf-new-project.jpg
  - /fig/osf-new-component.jpg
  - /fig/osf-doi.jpg
  - /fig/osf-go-to-new-project.jpg
  - /fig/osf-new-component-form.jpg
  - /fig/osf-new-project-form.jpg
  - /fig/osf-make-public.jpg
  - /fig/osf-component-id.jpg
  - /fig/osf-project-license.jpg
originalRepository: mjaquiery/jspsych-born-open-data
summary: We'll create a project and a data component on the OSF where we'll
  upload our data.

---
> #### Note:
> We'll be using the [test subdomain](https://test.osf.io/) of the OSF because we're testing things.
{: .challenge}

We'll be creating a new project on the Open Science Framework and adding a component which will house the data we upload.

1. Open [test.osf.io](https://test.osf.io/) in your browser and log in
2. Click 'Create new project'
![OSF new project screenshot]({% include installedFile.lqd path='/fig/osf-new-project.jpg' %})
Then fill in the form:
![OSF new project form screenshot]({% include installedFile.lqd path='/fig/osf-new-project-form.jpg' %})
Then click 'Go to project'
![OSF navigate to new project screenshot]({% include installedFile.lqd path='/fig/osf-go-to-new-project.jpg' %})
3. Create a new project component.
This component will house the data.
![OSF new component screenshot]({% include installedFile.lqd path='/fig/osf-new-component.jpg' %})
Fill in the form, making sure you select the **location** as `Germany - Frankfurt`.
![OSF new component form screenshot]({% include installedFile.lqd path='/fig/osf-new-component-form.jpg' %})
4. Navigate to the new component and give it an open license.
CC-BY 4.0 is a good license to use - people are free to reuse the contents provided that they acknowledge that they got it from you.
![OSF add license screenshot]({% include installedFile.lqd path='/fig/osf-project-license.jpg' %})
Now we have provided a license, let's make this component public.
Click 'Make Public'
![OSF make public screenshot]({% include installedFile.lqd path='/fig/osf-make-public.jpg' %})
5. Make a note of the component's id - we'll need that later.
You can find the id in the browser's address bar; it's the part that's highlighted in the screenshot below.
![OSF component identifier screenshot]({% include installedFile.lqd path='/fig/osf-component-id.jpg' %})

You're now all set up with an OSF project which has a special component ready to hold all the raw data.

> ## citing the repository
> Now that you have created a repository, copy the citation into the chat.
>
{: .challenge}

> ## DOIs and data citations
> You can create a DOI for your data to make it easy to cite. We wont do this now. 
> This is as simple as clicking the 'Create DOI' button and then confirming your choice.
> ![OSF create DOI screenshot]({% include installedFile.lqd path='/fig/osf-doi.jpg' %})
{: .challenge}



