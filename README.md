# Skillwill_Unit_Tests


1. Create a new Django project and app.
2. Write tests for a simple model. The model should have at least two fields and you should test the following:
   * Test that the model can be saved to the database.
   * Test that the model can be retrieved from the database.
   * Test that the model can be updated in the database.
   * Test that the model can be deleted from the database.
3. Write tests for a simple view that lists all the objects of the model you created in step 2.
   * Test that the view returns a status code of 200.
   * Test that the view returns a queryset of all the objects.
   * Test that the view returns the correct template.
4. Write tests for a simple form that allows you to create a new instance of the model you created in step 2.
   * Test that the form is valid with correct data.
   * Test that the form is invalid with incorrect data.
5. Write tests for a simple view that updates an instance of the model you created in step 2.
   * Test that the view returns a status code of 200.
   * Test that the view updates the object correctly.
   * Test that the view returns the correct template.
6. Write tests for a simple view that deletes an instance of the model you created in step 2.
   * Test that the view returns a status code of 302 (redirect).
   * Test that the view deletes the object correctly.
