#pdflatex is called twice to generate table of content
pdf: images
	pdflatex main.tex;
	pdflatex main.tex;

images:
	java -jar Umlet/umlet.jar -action=convert -format=pdf -filename=diagrams/layered_architecture.uxf -output=diagrams/layered_architecture.pdf;
	java -jar Umlet/umlet.jar -action=convert -format=pdf -filename=diagrams/data_stream_subsystem/kafka_cluster_use_case.uxf -output=diagrams/data_stream_subsystem/kafka_cluster_use_case.pdf;
	java -jar Umlet/umlet.jar -action=convert -format=pdf -filename=diagrams/navigation_subsystem/navigation_subsystem_draft.uxf -output=diagrams/navigation_subsystem/navigation_subsystem_draft.pdf;
	java -jar Umlet/umlet.jar -action=convert -format=pdf -filename=diagrams/navigation_subsystem/Navigation_subsystem_class_diagram_With_DesignP_draft.uxf -output=diagrams/navigation_subsystem/Navigation_subsystem_class_diagram_With_DesignP_draft.pdf;
	java -jar Umlet/umlet.jar -action=convert -format=pdf -filename=diagrams/data_stream_subsystem/data_stream_api.uxf -output=diagrams/data_stream_subsystem/data_stream_api.pdf;
	java -jar Umlet/umlet.jar -action=convert -format=pdf -filename=diagrams/users_subsystem/users_subsystem.uxf -output=diagrams/users_subsystem/users_subsystem.pdf;
	java -jar Umlet/umlet.jar -action=convert -format=pdf -filename=diagrams/users_subsystem/users_class_diagram.uxf -output=diagrams/users_subsystem/users_class_diagram.pdf;
	java -jar Umlet/umlet.jar -action=convert -format=pdf -filename=diagrams/users_subsystem/users_factory_design_pattern.uxf -output=diagrams/users_subsystem/users_factory_design_pattern.pdf;
	java -jar Umlet/umlet.jar -action=convert -format=pdf -filename=diagrams/gis_subsystem/GIS_Class_Diagram.uxf -output=diagrams/gis_subsystem/GIS_Class_Diagram.pdf;
	java -jar Umlet/umlet.jar -action=convert -format=pdf -filename=diagrams/gis_subsystem/subsystem_gis_use_case.uxf -output=diagrams/gis_subsystem/subsystem_gis_use_case.pdf;
	java -jar Umlet/umlet.jar -action=convert -format=pdf -filename=diagrams/deployment_diagram.uxf -output=diagrams/deployment_diagram.pdf;

clean:
	rm main.aux main.log main.out main.pdf main.toc

